Video preview : https://youtu.be/Gcie_bWVssM


How to run the code:
    First load all the gradle dependencies
    Loading the gradle

    Then run the AngryBirds-main:lwjgl3:run task
    Display window will open.



Angry Bird :

    Code Starts with the Main class which is the entry point of the game.
    The Main class is responsible for creating the game window and setting up the game loop.
    Main class set screen to the MainMenu class.

    In every screen we have a back button so we can  go back to the previous screen

    MainMenu class is responsible for displaying the main menu of the game.
    It has the features to set the basics of the game like display,Music,Viewpoint etc.
    It redirects to the MainMenuButtons class when the user clicks on the screen.

    MainMenuButtons class is responsible for displaying the buttons on the main menu.

    Game screen is the screen for choosing between three levels level 1 level 2 level 3
    It redirects to the Game class when the user clicks on the screen.
    Game screen leads us to levelscreen where we can choose between a new level or a previously loaded level.

    Now Go over the LevelScreen,in a level we have a "RANDOM LEVEL GENERATOR" we have three kinds of pigs professor pig normal pig King pig
    and we have three types of birds Red Terence and silver.
    We have to first set up the trajectory of a catapult and by pressing "H" we can launch the given bird at that trajectory.

    We have implemented the physics at the working of game using box 2D
    We redirect the screen with the appropriate mapping of the screen.

    We have implemented the sound effects in the game.

    We have collision detection in the game.
    In  collision detection we have implemented the collision between the bird and the pig.
    We have implemented the collision between the bird and the ground.
    We have implemented the collision between the bird and the block.
    and all the other combinations.

    Now Maintain a Arraylist of birds and pigs which is handling
    When there is a pig left and we have no bird left then we lose that level
    When there is no pig left we will loose the level.

    Every big every bird at every block has a health
    associated with it the health depends on the type of word or a type of pig or the type of block

    When two bodies collide they both take some damage in their health via factor of the velocity with which they collided
    A big is considered to be dead if it if it's help is negative or zero.

    For saving a state of a game we have recorded health position linear velocity
    and type for each bird similarly for pig and same for a block so in total we have 12 parameters and
    we are saving it in a binary file.
    To load the level we are taking that data from dad binary file and placing all the birds pigs at blogs to their
    position with their respective velocity with their respective health and of their type.

Oops :

        1. We have implemented the concept of inheritance in the game.
            Ground1 extends sprite class
            Platform extends sprite class and implements the Serializable interface

        2 .We have implemented the concept of polymorphism in the game.
            Used In constructor of Play1 , Play2 and Play3

        3. We have implemented the concept of encapsulation in the game.

        4. We have implemented the concept of constructor in the game.
        5. We have implemented the concept of destructor in the game.
        6. We have implemented the concept of static in the game.
        7. We have implemented the concept of final in the game.
        8. We have implemented the concept of super in the game.
        9. We have implemented the concept of this in the game.


