# Middlegame_Chess
Want to play Chess but tired of memorising openings? This variant of chess loads a developed position deemed equal for White and Black by Stockfish (Depth = 20). 

### Definitions ###
There is no definite way to classify any position that represents the end of the Opening and the start of the Middlegame. It is possible to use the stockfish analysis of all initial move orders to determine which move establishes the confirmation of an Opening, however the positional database does not keep track of move orders and only stores FEN positions. Hence a rough estimate would be a position obtained after at least 10 moves. To ensure that it will not quickly evolve into a drawn endgame, initial positions will require at least all but 2 pieces to be remaining on the board.

What defines an "equal" starting Middlegame position? For humans up to GM rating, it is unlikely any player can get an advantage with a Stockfish evalutation of up to +/- 0.3. As such, all starting positions will lie within the range of -0.3 to + 0.3 evaluated by Stockfish with 20 Depth. 

### Rules ###
Since evaluation of any Middlegame position can vary greatly depending on whether it is Black's turn or White's turn, in this Variant either White or Black will be given the first move. 

### FYI ###
A similar concept was played at the CasaBlanca Chess 2024 Tournament by Chess.com, but no official variant is available online. However in this tournament 
