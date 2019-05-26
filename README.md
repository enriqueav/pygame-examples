# pygame-examples
Simple examples of pygame. **Just for fun**.

The only dependency, for now, is pygame

`pip install pygame`



### bouncing_balls.py

A simple example of a group of balls with random colors and speeds. 
They bounce on the limits of the screen. No collision detection is implemented (yet).

To run:

```python
python bouncing_balls.py [number_of_balls]
```
![Capture01](https://github.com/enriqueav/pygame-examples/raw/master/images/bouncing.gif)

## Parallax Examples

*Parallax scrolling is a technique in computer graphics 
where background images move past the camera more slowly 
than foreground images, creating an illusion of depth 
in a 2D scene and adding to the sense of immersion in 
the virtual experience.[1] The technique grew out of 
the multiplane camera technique used in traditional 
animation since the 1930s.* From [wikipedia](https://en.wikipedia.org/wiki/Parallax_scrolling)

### parallax_city.py

This example programmatically creates a moving background with three layers.

To run:

```python
python parallax_city.py
```
![Capture02](https://github.com/enriqueav/pygame-examples/raw/master/images/parallax_city.gif)


### paralax_beach.py

This example programmatically creates three layers of sea and three layers of sand.
They follow an smooth sine curve.

I **do not** recommend drawing curves as a series of bars like this example, 
it is too slow to process. I have not figured out
the best way to do it in pygame yet.

To run:

```python
python parallax_beach.py
```
![Capture03](https://github.com/enriqueav/pygame-examples/raw/master/images/parallax_beach.gif)
