# Oh boy, the house has trapped you!

A simple game that stores only a few variables,

more of an exercise of how to write a 'choose your own adventure' in twine!

## The Web

The code looks very much like a web:

### Start

- $cabinet
When you find the cabinet, after looking through the house, its set to true.  Otherwise, it is set to false at the start.
- $key
After looking through the cabinet, the key is found, $key is set to true.

### Oh Boy

The key to all the logic, this is where you can search the room, go to the door, or search the cabinet.  After finding the cabinet, your options change to go to the door or search the cabinet.

### look

When you look through the room, you will find the door in cabinet, it sets $cabinet to true, and gives you the ability to go back.

If you have found the key, it allows you to use the key and win.

### search

All it does is allow you to search through the cabinet, sets $key to true.

### win

You escaped!  You can now start the game again.

## Twine

A simple choose your own adventure engine that is very powerful.

It stores nodes with just a name and position, the user only needs to press new, and write a name to make a new node.

To switch between nodes, you only have to write a simple transition following this format: '[[message to player->node name]].' This is all it takes to have a simple transition to another node.

## Reflection

Although I didn't have much time to develop on twine, it is quite the platform.  The hardest part is actually coming up with the ideas for what to do.

Personally, I like how it uses variables to change previous nodes, which is something that can be very powerful.
