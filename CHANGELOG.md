
- tag Coord class for Json parsing
- tag GameResult enum, add a String result to the constructor for Json parsing
- add ShipAdapter record
- removed Player argument for Controller class and Board class - Unused and recommended by last TA
-
- to Ship, add getStart method, add getDir to help with creating Json records for a Ship
- in aiPlayer class, delegates takeShots to aiPlayerTakeShots method in Shots class
- in AiPlayer class, added shootX and shootY fields to keep track of where to shoot
- in Shots class, added aiPlayerTakeShots method
- changed aiPlayerTakeShots to shoot in rows instead of randomly
- 