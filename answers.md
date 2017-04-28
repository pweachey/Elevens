##1. Size is an instance variable. There is no reason to create setters or getter methods in the Board class.

##2. Removing and replacing cards is normal regardless of which game is being played. It can be implemented in the Board class.

##3. isLegal. and anotherPlayIsPossible. would still be called polymorphically. This can still work but all of the methods will have to be imputed separately.