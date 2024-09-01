A small RPG game made in C# and .NET used to learn and experiment with the .NET framework.

-> Base project forked for a university .NET class and updated over-time with improvements

## Personal Contributions

Added hitboxes for trees

- Used tiled object layer to add rectangles representing the hitboxes ( the trees in this case ),
- Parsed the .tmj file and separated the object layers as being "hitbox" layers,
- Added ability to see the hitboxes by holding "h" while playing.

Added player/bomb collision for hitboxes

- Checked for player collision: player cannot pass hitboxes
- Checked for bomb collision: cannot place bomb on hitboxes

Fixed assets retrieval and bomb behaviour.
Added ClearResources function and support for opacity + layers.
