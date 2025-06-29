# typegun

> Special Gun Special\
—_Super Smash Bros. Ultimate_

Typegun is a small command-line utility for python to run a bunch of python typecheckers on a project, to see if there are any problems. This grew out of a script I would cart around, which I decided to make a reusable package. TODO: actually put it in here, and publish this package on pypi.

This only includes typecheckers that have a reasonable shot at typing near-current-version python projects mostly-correctly, in my (non-scientific) opinion, a list which may vary over time. If you'd like to add more or bicker about the configurations these typecheckers should have, I'm happy to hear it. The versions of these typecheckers are completely unpinned, all the better to get the most recent versions of them probably. It also includes [ruff](https://docs.astral.sh/ruff/), which is not a typechecker, but is very useful for code quality nonetheless.

As of right now, typegun forces your system to use pip to install uv system-wide, and then uses uv to install the typecheckers into a local venv.

TODO: allow for custom behavior thru a typegun_special file or something.

TODO: example usage using pipx or w/e

## Illustrative diagram

![poorly-drawn cartoon image of a man firing a shotgun (the bullets of which have been labeled "mypy", "pyright", etc) at a python project](readme_diagram.png)
