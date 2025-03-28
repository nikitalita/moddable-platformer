# Moddable Platformer

This mini moddable game project by [Endless OS
Foundation](https://endlessos.org) is intended to help ease the learning curve
into Godot.

This sample project allows learners to engage with game creation concepts,
applying various modifications to the game itself, all without reading or
writing any code.

The `doc/MODS.md` file details the mods that have been made available.

## Running patchwork plugin

You need to init the Patchwork submodule

```
git submodule init
```

Starting godot with the following command ensures that the rust plugin is always rebuild

```
run.sh
```

## Contributing

We encourage contributions that continue to address the intended audience and
design of of this project. You can communicate with us through the [Endless
Studios](https://endlessstudios.com/studio/games/Moddable-Platformer) community
platform and submit pull requests via
[GitHub](https://github.com/endlessm/moddable-platformer).

### Development environment

Please use [pre-commit](https://pre-commit.com) to check for correct formatting
and other issues before creating commits. To do this automatically, you can add
it as a git hook:

```
# If you don't have pre-commit already:
pip install pre-commit

# Setup git hook:
pre-commit install
```

Now `pre-commit` will run automatically on `git commit`!
