# misc-projects-py
Just a collection of projects I made for fun in python. Most were made *back in 2018*, so the code ain't the prettiest!



__ballimation__ is just a series of 2D bouncy ball simulations.

**v1 :** standard function-based simulation
**v2 :** class-based simulation w/ many more *planned* features, like variable gravity angle, non-rectangular walls etc. *Currently incomplete* and not 100% debugged, however... might finish someday. sfx assets taken from an osu skin



__chaos game__ plays [the Chaos Game](https://www.youtube.com/watch?v=kbKtFN71Lfs).

**chaos_game :** first Turtle-based version, extremely slow
**chaos_game_gif_generator :** cycles through different no. of vertices and movement ratios to make gifs. Was my own idea to animate different things by altering a variable in small increments (like Mandelbrot images)
**chaos_game_vPygame :** 2022 update with pygame, bringing alright speed



__complex to the power n__ is a set of graphing programs that graphs successive iterations of z(n) = z(n-1)^k or similar.

**pygame_complex^n :** standard equation. Shows that the "orbits" of z(n) = z(n-1)^k diverge when |z0| > 1, so the Mandelbrot set equivalent for this is just a circle
**pygame_complex^n_vMandelbrot :** Mandelbrot equation, z(n) = z(n-1)^2 + c! Can trace out the boundary of the set with this



__times tables__ is an implementation of [Mathologer's times tables](https://www.youtube.com/watch?v=qhbuKbxJsk8).

**times_table_visualiser_colour :** standard, shows a nice animation as the table is built up. If that's too slow, just set TRACER_ACTIVE to False
**times_table_visualiser gif creator :** makes gifs by cycling through different parameters, again. Pretty fond of these gif makers!



__click measurer__ measures CPS (allowing both mouse and z/x clicks). Also has a highscore system?


__diffusion__ is a simulation of diffusion through random (Brownian?) motion.


__everything formula__ is an implementation of [Tucker's "everything" formula](https://www.youtube.com/watch?v=_s5RFgd59ao), made as a birthday gift for a friend (so it only finds the k value for a pre-included image; anything with the same resolution should work too though, just replace ali.jpg).


__terraria image mod maker__ is a... very specific program, which autogenerates a tModLoader mod that only contains one item: the image input to the program.