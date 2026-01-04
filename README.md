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

This project has two components.
It started off as an exploration of cartographic hillshading as well as a way to utilize `stf` in a real project.
But it also grew to be the basis for a submission in the Summer of Math Exposition 4 ([SoME](https://some.3b1b.co/)).

This is a really fun project because it shows how pretty simple mathematics can be the basis for producing realistic output in computer graphics.
I enjoyed putting together the video and I have a new respect for those who do so regularly.
It was a significant time investment!

The image on the left is linked to the video and the animation on the right demonstrates the project in action. 
My submission to SoME is linked [here](https://some.3b1b.co/entries/92b0be7a-12f7-42f4-bca6-c20f20a8e19b).

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