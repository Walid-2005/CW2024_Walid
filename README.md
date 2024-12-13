# Project Title: Retro_Game

## Compilation Instructions
- **Step 1:** Ensure that all Java classes are in the same file or package.
- **Step 2:** The application requires JavaFX to run. Ensure that JavaFX is correctly installed and configured in your development environment.
- **Step 3:** Open a new terminal on intellij
- **Step 4:** Enter this command " cd ElHansyWalid_intellij_11.0.25 "
- **Step 5:** Then proceed to Enter this command " mvn javafx:run "

## Implemented Features that function 
- **Restart button for all three levels:** All three restart buttons work as expected, offering smooth gameplay.

- **Kill count:**  allows user to track his kill stats during level 1.

- **Audio enhancements:** Sounds are played when player wins the entire game or loses a level, enhancing the overall gaming experience.

- **Level count:** allows user to track which level he is currently at.

- **Stop button:** a button implemented along with the restart button to end the game when user is done.


## Implemented but is not Working as expected
- **Collision Detection System:** The collision detection remains inconsistent, even after adjusting the element's height to help resolve the issue and trying to pinpoint the source of the problem.

## New Java Classes
- **SoundPlayer:** It retrieves the sound file's resource path, creates a Media object, initializes a MediaPlayer to play it.

- **LevelThree:** A new level has been introduced where the player and the boss can move freely in all directions, with updated background visuals and redesigned projectiles.


## Modified Java Classes

- **LevelParent:** 
The LevelParent class serves as the foundation for all levels, providing core functionalities
such as tracking the kill count and level count. It also includes features like sound effects
for game events, including winning and losing, which enhance the overall immersive experience.

- **LevelOne:** 
    I implemented a kill count display that dynamically updates as the player defeats enemies.
    This feature is achieved using a Label that updates with the player's current kill count,
    enhancing gameplay feedback. Additionally, I fixed an issue in the LevelParent class where
    hearts representing the player's health would disappear prematurely, ensuring they
    correctly reflect the player's health throughout the level.

- **LevelTwo:** 
 The level also features a level counter that displays the current level number on the screen,
 providing players with a sense of progression

There have been updates to the Boss, BossProjectile, EnemyPlane, EnemyProjectile, FighterPlane,
UserPlane, and UserProjectile classes to adjust image heights. While debugging in Level One,
Level Two, and LevelParent, I resolved issues where hearts representing health were
disappearing without collisions and ensured that enemy projectiles could successfully reach the
user's plane, enhancing gameplay mechanics and realism.

## Unexpected Problems
1. **shield not appearing in level 2:** 

