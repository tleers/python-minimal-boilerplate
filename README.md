## Project title

This boilerplate project contains the following setup ready for you to go. 

We choose rye, which combines package/environment and dependency management, as well as linting, formatting & testing. 

We use `mypy` for static type checking.

# Setup

1. Clone this repo
2. Make sure to [install Rye](https://rye.astral.sh/guide/installation/)
3. In your project directory run
   1. `rye sync`
   2. `pre-commit install`
4. On each `git commit` the code validation packages will be run before the actual commit.
5. Explore the setup in the folder structure of this package.
6. Profit.