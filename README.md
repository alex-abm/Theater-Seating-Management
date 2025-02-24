# Theater-Seating-Management

The TheaterSeating system models an 
n
×
m
n×m seating arrangement in a theater, categorizing seats as Outer Seats (OT) at the edges, Middle Seats (MT) at the center of each row, and Inner Seats (IT) for all others. Gifts are placed on seats where the sum of row and column indices is odd. The system supports various operations, including retrieving the initial number of gifts (getAmountOfGifts), tracking remaining gifts (totalTakenGifts), booking the first available or specific seats (bookSeat), and reserving seats based on type preferences (bookTailoredEmptySeat). Spectators can book seats using different methods: bookAnySeat for the first available seat, bookSpecificSeat for a chosen seat, and bookATailoredSeat, which assigns seats based on the spectator’s name—short names get outer seats, even-length names prefer the left side, and regular names receive middle seats. Spectators can also take gifts from their assigned seats. The system is validated through JUnit 5 tests, ensuring correct seat assignment, gift initialization, booking logic, and spectator interactions.
