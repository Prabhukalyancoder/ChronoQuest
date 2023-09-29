# ChronoQuest
A simple text based adventure game in java
This code defines a simple text-based game with a graphical interface using Java's Swing library. It sets up various game states, allows the player to make choices, and updates the game's narrative accordingly.


import java.awt.Color;
import java.awt.Container;
import java.awt.Font;
import java.awt.GridLayout;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;

import javax.swing.ImageIcon;
import javax.swing.JButton;
import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JPanel;
import javax.swing.JTextArea;
This section of code imports necessary classes and packages for creating a graphical Java game using Swing.


public class Game {
    // Class members including JFrame, fonts, buttons, and game state variables.
This is the declaration of the main Game class, which contains various attributes and methods for creating and managing the game.


    public static void main(String[] args) {
        new Game();
    }
The main method is the entry point of the program. It creates an instance of the Game class to start the game.


    public Game(){
        // Constructor for initializing the game window.
    }
This is the constructor of the Game class responsible for setting up the game's graphical user interface (GUI).


    public void createGameScreen(){
        // Method for creating the main game screen with text areas and buttons.
    }
This method creates the main game screen with text areas for displaying the game's narrative and buttons for player interaction.

    public void playerSetup(){
        // Method for initializing player attributes and starting the game.
    }
playerSetup initializes the player's attributes such as HP, weapon, and sets the initial game state.


    public void townGate(){
        // Method for displaying the starting town gate scenario.
    }
townGate method sets the game state to the town gate scenario, where the player encounters a guard.


    public class TitleScreenHandler implements ActionListener{
        // ActionListener for handling events in the title screen.
    }
TitleScreenHandler is an inner class responsible for handling events in the title screen, such as starting the game.


    public class ChoiceHandler implements ActionListener{
        // ActionListener for handling player choices and game progression.
    }
ChoiceHandler is another inner class responsible for handling player choices and advancing the game's storyline based on those choices.

This code defines a simple text-based game with a graphical interface using Java's Swing library. It sets up various game states, allows the player to make choices, and updates the game's narrative accordingly.
