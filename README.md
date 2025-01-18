Secret Word is a React-based game inspired by the popular Brazilian TV show Roda a Roda Jequiti. The game is designed to challenge players to guess a hidden word by revealing letters based on their selections, similar to a word guessing game format.

Key Features of the Secret Word Project:
Gameplay:

The game features a word that is hidden at the start, and the player needs to guess it by selecting letters.
Each correct letter that appears in the word is revealed to the player, while incorrect guesses may trigger a penalty (such as losing points or chances).
Players continue guessing letters until they reveal the entire word or run out of attempts.
React Components:

The user interface is built using React components for flexibility and maintainability.
Components are structured for the word display, letter choices, and the game’s score or attempts display.
State Management:

React’s built-in hooks (such as useState and useEffect) are used to manage game states, including the word being guessed, player input, score, and the number of remaining attempts.
The game logic is encapsulated in components to handle things like tracking the revealed letters and checking whether the player's guess is correct.
React Router:

React Router is used to navigate between different game states, such as the welcome screen, game screen, and the end game screen (win/lose).
