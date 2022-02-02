# Gameplay 

## Power-ups

| Index | Power-up                  | Description                                                  |
| ----- | ------------------------- | ------------------------------------------------------------ |
| 1.0   | Brake wall                | Ram can bump his head in a wall to destroy it.               |
| 1.1   | Switch player             | Player 1 becomes player 2 (screens layout stays the same)    |
| 1.2   | Invert opponents controls | Left becomes Right and Up becomes down this works vice versa |
| 1.3   | Shield                    | add extra life (can be hit by a bullet from a hunter)        |
| 1.4   | Invisible maze            | Opposite player gets a black screen for a few seconds (can still move) |
| 1.5   | Slow motion               | Hit controls twice to move in the direction                  |
| 1.6   | Speedup                   | Move all the way foreword until the ram hits a wall          |
| 1.7   | Mystery Box               | Can be one of the above power-ups                            |



## User inputs

| Index | User inputs               | Description                |
| ----- | ------------------------- | -------------------------- |
| 2.0   | (Joystick) Left           | Move left                  |
| 2.1   | (Joystick) Right          | Move right                 |
| 2.2   | (Joystick) Up             | Move up                    |
| 2.3   | (Joystick) Down           | Move down                  |
| 2.4   | (Button) Pick up power-up | Picks up the power up      |
| 2.5   | (Button) Use power-up     | Use the picked up power up |
| 2.6   | (Button) Open menu        | Opens the control menu     |

## Character mechanics 

| index | User input index | In game movement | Description                                                  |
| ----- | ---------------- | ---------------- | ------------------------------------------------------------ |
| 3.0   | 2.0              | Moving left      | Ram moves one step to the left when facing left, otherwise the ram rotates left first. |
| 3.1   | 2.1              | Moving right     | Ram moves one step to the right when facing right, otherwise the ram rotates left first. |
| 3.2   | 2.2              | Moving up        | Ram moves one step foreword when facing forewords, otherwise the ram rotates up first. |
| 3.3   | 2.3              | Moving down      | Ram moves one step backward when facing backwords, otherwise the ram rotates down first. |
| 3.4   | 2.4              | Pick up power-up | When the ram is on top of a power-up object it will pick it up. |
| 3.5   | 2.5              | Use power-up     | Picks up the power-up and add it to the players power up pallet. |
| 3.6   | 2.6              | Open menu        | Opens the config menu, the game is paused menu can be controlled by player 1 joystick. |

