# About

Hi! I am a software engineer with degrees in both applied mathematics and computer science.
I have a deep love for learning and enjoy working on hard problems.

I have a special interest in working with computer graphics as it is a particularly challenging combination of mathematics and computer science.
Some of my favorite areas to work in are vectors/matrices, 3D camera transformations, volume intersection, computational geometry, and multithreading.
Though there are many other interesting areas as well!

On this site, you will see some projects that I have chosen to highlight.

# Projects

## stf

repo: https://github.com/nathanstouffer/stf

docs: https://nathanstouffer.github.io/stf/docs/dev/

`stf` is a C++ math library built primarily for graphics.
It provides graphics primitives useful for 2D and 3D rendering (e.g. vector, matrix, polyline, camera, frustum).
The library is templated so that each primitive can be used with a different number type (int/float/double) based on the needs of consuming code.

One thing I am particularly happy with is the functions that compute whether or not `aabb3`/`obb3`/`frustum` objects intersect.
Many implementations of intersection functions use a strategy that results in false positives (`intersects` returns `true` even if the two objects do not intersect).
The implementation I use does a more thorough check and does not return false positives.

## hillshade

repo: https://github.com/nathanstouffer/hillshade

<div style="display: flex; justify-content: center; gap: 1%; flex-wrap: wrap; align-items: flex-start;">
  <a href="https://www.youtube.com/watch?v=Xd1uwJ6biU4" 
     target="_blank" rel="noopener noreferrer" 
     style="width: 49.5%; display: block;">
    <img src="https://img.youtube.com/vi/Xd1uwJ6biU4/maxresdefault.jpg" 
         alt="Hillshade Explainer Video" 
         style="width: 100%; height: auto; border-radius: 0.5rem;">
  </a>
  <video 
      autoplay muted loop playsinline 
      src="assets/orbit-loop.mp4" 
      title="Hillshade demo" 
      style="width: 49.5%; height: auto; border-radius: 0.5rem;">
  </video>
</div>

## fractals

repo: https://github.com/nathanstouffer/fractals