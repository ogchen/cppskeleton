# C++ Skeleton

A C++ project skeleton based on the [Pitchfork Layout](https://api.csswg.org/bikeshed/?force=1&url=https://raw.githubusercontent.com/vector-of-bool/pitchfork/develop/data/spec.bs)

## Directory Structure
* `include/` - Public headers.
* `src/` - Source files, private headers and unit tests.
* `tests/` - Non-unit tests.
* `examples/` - Example usage of project.
* `external/` - Embedded external projects. Can be automatically populated but must be git ignored.
* `data/` - Project files that are not code.
* `tools/` - Extra scripts/tools related to development and contribution. For example, turn-key build scripts, linting scripts, code-generation scripts, test scripts.
* `docs/` - Project documentation.
* `libs/` - Used only if project is subdivided into submodules. Replaces `include/` and `src/` (alongside `tests/`, `data/`, `examples/` and `docs/` if present).
* `extras/` - Extra submodules that are not part of the project's "default" build.
