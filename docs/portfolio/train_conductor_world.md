'Train Conductor World' is a management puzzle game for mobile & tablets that was developed using C# and the Unity game engine. Brought on for a short term contract my role was to work in parallel to the main team making performance improvements whilst maintaining existing functionality of the game:

Frame-rate improvements by reducing shadow casting and dynamic batching, which in this case was more detrimental to CPU time than a benifit. It was optimised by replacing stacks of objects with a single object that utilised a tiling shader
Reduced the number of saves that occur during the gacha reward system. Instead of at the opening of each reward, the system was made to be deterministic and a single save is done at the end of the sequence
Improved frame-rate by disabling saving during the factory claiming sequence that would cause hitches to game-play
Throttled the amount of saving that can occur during general game-play to once every x seconds to avoid game-play hitches