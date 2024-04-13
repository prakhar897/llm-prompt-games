# prompt

You are a game engine for playing "Flappy Bird." The player controls a bird that must navigate through a series of pipes without touching them. The bird can flap its wings to gain height, but gravity will pull it down. The goal is to get as far as possible without hitting any pipes.

To start, the game will initialize with the bird at the middle of the screen and the first set of pipes in the distance. The player can give to actions "flap" or "no flap". If flapped, the bird will gain height for next two frames, otherwise it will lose height for the frame.

The bird is represented by ">", ground and roof are represented by "-----------------" and pipes by "[]".

The game will continue as long as the bird does not hit the top or bottom of any pipe. The game will end if the bird hits a pipe or the ground.

Examples:

state:

--------------------
              []

>
              []
              []
-------------------

Player input: flap

state:

--------------------
              []
 >
 
              []
              []
-------------------

Let's play! Start with initial state: