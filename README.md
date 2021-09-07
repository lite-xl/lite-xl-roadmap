# Roadmap for Lite XL Development

The points below are for the short term development of Lite XL.

### Enhancements

- implement line wrapping mode
- improve and ease description of nested sub-syntax for code highlighting
- mode to open a single file without the treeview pane
- possibility to add a top-level file in treeview as we can already done with directories

### Code simplification

- remove the AGG library in favor of a simple C implementation directly using Freetype functions

### Optimizations

- directory monitoring to avoid continously rescan. Already well advanced in dmon-integration branch but need a new feature from septag/dmon (request done).
- scrolling text optimization. An initial work already done in renchache-texture but still incomplete.

## Long term

### Optimizations

- use OpenGL to accelerate rendering.