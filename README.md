# 15129093-Karl-Winfelt
Pong

Goal :

For win the game Player need to send a ball in the opponent goal.  
When the player win 10 times the player win the game.

Game World :

- Two paddles.
- One ball.
- Goal line.
- Limit line.

Rules :

When the game start ball go on random direction between tow player.
When the ball touch a paddle or limit line the ball rebounce.
The speed of the ball increases during the game.
When the ball touch Goal line of his opponent player win 1 point.

Game Player :

Game player use 2 key for move ((up or down) or (left or right)).
Player Can play versus AI or Human.


Use Case :

Player :
 - Select Mode (AI or 2 Players)

AI Mode :
 - Select level AI
 - Game Start


2 Player Mode :
 - Game Start

Game Start :
 - CPU Control one paddle (AI mode).
 - Player control one paddle with 2 key (2 Players Mode : second Player control other paddle with other key).
 - CPU reset ball for each point.
 - End Game when max score is reaches.



