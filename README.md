# PathFinder

SFML - Simple and Fast Multimedia Library
SFML is multimedia.
SFML provides a simple interface to the various components of your PC, to ease the development of games and multimedia applications. It is composed of five modules: system, window, graphics, audio and network.

SFML is a multimedia library, meaning that it provides a layer between you and the hardware. It is split into five modules:

System: This is a core module upon which all other modules are built. It provides two-dimensional and three-dimensional vector classes, clocks, threads, and Unicode strings, among other things.

Window: The Window module makes it possible to create application windows, and to collect user input, such as mouse movement or key presses.

Graphics: This module provides all functionalities that are related to two-dimensional rendering, such as images, texts, shapes, and colors.

Audio: SFML also offers a module to work with sound. When you want to load a music theme and play it on the computer's loudspeakers, this is the module you have to look for.

Network: Another medium SFML covers is the network, a more and more important part of our interconnected world. This module allows you to send data over LAN or the Internet; it also lets you work with protocols, such as HTTP or FTP.

# Implementation of Dijkstra : - 

Start from the given source cell in the matrix and explore all four possible paths.
Check if the destination is reached or not.
Explore all the paths and backtrack if destination is not reached.
And also keep track of visited cells using an array.

Valid Moves are:

 left: (i, j) ——> (i, j – 1)
 
 right: (i, j) ——> (i, j + 1)
 
 top: (i, j) ——> (i - 1, j)
 
 bottom: (i, j) ——> (i + 1, j )
 
# Implementation of A* : - 
 
 A* expands paths that are already less expensive by using this function:
 
f(n)=g(n)+h(n),
wher
f(n) = total estimated cost of path through node 

g(n) = cost so far to reach node n

h(n) = estimated cost from n to goal. This is the heuristic part of the cost function, so it is like a guess.

