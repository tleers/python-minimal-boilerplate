## Project title

This boilerplate project contains the following setup ready for you to go. 

We choose rye, which combines package/environment and dependency management, as well as linting & formatting. 

We use `pylyzer` for static type checking (faster mypy).

# Setup

1. Clone this repo
2. Make sure to [install Rye](https://rye.astral.sh/guide/installation/)
3. In your project directory run
   1. `rye sync`
   2. `pre-commit install`
4. On each `git commit` the code validation packages will be run before the actual commit.
5. Explore the setup in the folder structure of this package.
6. Profit.

# Rationalisation

1. Src layout instead of flat layout
2. Pre-commit flow + github actions
 * here is the github workflow CI which performs more extended checks or repo-specific checks.
 * there is the pre-commit flow which is more lightweight, can be developer-specific as well
