Constructor Pattern:
The Constructor pattern is used to create a single instance of the Telephone class, which stores phone contacts and observers.

Singleton Pattern:
The Singleton pattern is implemented in the Telephone class to ensure only one instance is created.

Factory Pattern:
The Factory pattern is used to create individual phone number objects with a function PhoneNumber.

Observer Pattern:
The Observer pattern is used to notify observers about changes in the phone contacts. They receive updates when a phone number is dialed.

Prototype Pattern:
The PhoneNumber class uses the Prototype pattern by having its instance's properties (firstName, lastName, number) shared among all instances of the class, so that any instance can use them without having to recreate them.


HOW TO USE :
Clone or fork the repository into your vscode terminal 
reun the command: node index.js