# Object-Management

| Index | Content             | Detail                                                       |
| ----- | ------------------- | ------------------------------------------------------------ |
| 01    | Persisting Objects  | Spawn random cubes in response to a key press<br />Use a generic type and virtual methods<br />Write data to a file and read it back<br />Save the game state so it can be loaded later<br />Encapsulate the details of persisting data |
| 02    | Object Variety      | Create a factory for shapes<br />Save and load shape identifiers<br />Support multiple materials and random colors<br />Enable GPU instancing |
| 03    | Reusing Objects     | Destroy shapes<br />Automate creation and destruction<br />Build a simple GUI<br />Track memory allocations with the profiler<br />Use objects pools to recycle shapes |
| 04    | Multiple Scenes     | Create a scene in play mode<br />Move objects between scenes<br />Work with multiple scenes<br />Support game levels |
| 05    | Spawn Zones         | Create a spawn zone and transform it<br />Use gizmos to visualize spawn zones<br />Support a different spawn zone per scene<br />Connect objects from different scenes<br />Create multiple spawn zone types |
| 06    | More Game State     | Keep track of randomness<br />Save level data<br />Loop through spawn zones<br />Create a rotating level object |
| 07    | Configuring Shapes  | Make shapes rotate and move<br />Centralize game updates<br />Add configuration per spawn zone<br />Improve the inspector |
| 08    | More Factories      | Create composite shapes<br />Support multiple colors per shape<br />Select factories per spawn zone<br />Keep track of a shape's origin factory |
| 09    | Shape Behavior      | Define abstract and concrete behavior for shapes<br />Only include behavior when needed<br />Create a generic method and class<br />Use conditional compilation<br />Add a method to an enumeration<br />Make Shapes oscillate |
| 10    | Satellites          | Spawn multiple shapes at once<br />Make a shape orbit another shape<br />Keep track of references to specific shape instances<br />Enforce a shape population limit |
| 11    | Lifecycle           | Make shapes grow and shrink<br />Allow behavior to kill shapes<br />Delay killing until after the game update loop<br />Replace immediate shape destruction with shrinking |
| 12    | More Complex Levels | Make spawning automatic<br />Create zones antithetical to or essential for life<br />Control which zones affect which shapes<br />Centralize level object updates and add editor support<br />Use partial classes |