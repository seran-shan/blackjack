## Simple Blackjack game in Java, with GUI
by Joseph Rautenbach, 17 September 2015

![Main image](http://i.imgur.com/tibL3bM.png)

###About
This is a one-player blackjack game, where the player plays against the dealer.

###Implementation
The game is written in Java (developed in Eclipse) using Swing/AWT for the GUI.
Each card is an instance of `Card`, stored in a `CardGroup` and the contents of a `CardGroup` can be displayed as a `CardGroupPanel`, an extension of Swing's `JPanel`.
The code is well commented so should be pretty easy to understand.

###Gameplay
The player sets an initial balance, deals and then hits or stands until either getting a blackjack, winning, losing or pushing.
When out of money the option to top up or end the game is given.

###How to Build
This project was developed in Eclipse, so it's easy to just import the project directly into Eclipse and run.
Otherwise, simply compile the .java sources in `src`, and be sure to include the image resources in the repo root.