# Space Shooter

![window example result](screenshot.png)

A simple 2D space-shooter game that demonstrates how to make a game using the [Amethyst](https://github.com/amethyst/amethyst) game engine.

This is a simple space-shooter game where you manipulate your space ship using right and left thrusters (A and D) and fire lasers
(spacebar) to destroy the falling asteroids. If you get hit by three asteroids--game over!

It demonstrates some common game-design patterns in Component Object Programming (COP), also known as Entity Component Systems (ECS).

It is fully documented, so you can use it as a learning resource.

To compile, you need to specify the graphics backend, e.g.

```shell script
cargo build --features "metal"
```

or

```shell script
cargo build --features "vulkan"
```

The assets are supplied from by Kenney Vleugels (www.kenney.nl) under [Creative Commons Licence CC0](http://creativecommons.org/publicdomain/zero/1.0/).

Code is supplied under Apache License 2.0 and the MIT License. See the appropriate license files for more information.

All other text and documentation is supplied under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
