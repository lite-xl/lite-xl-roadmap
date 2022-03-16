# Roadmap for Lite XL Development

The points below are for the short term development of Lite XL.

### Enhancements

- implement line wrapping mode
- improve and ease description of nested sub-syntax for code highlighting
- mode to open a single file without the treeview pane
- possibility to add a top-level file in treeview as we can already done with directories
- fix keymap binding on non-US keyboard when the required key has to be done using shift
- Support adding font styles to the patterns of syntax files, for details see
  [#864](https://github.com/lite-xl/lite-xl/pull/864#issuecomment-1060008067)

### Problems to fix

- on Windows, when in borderless mode, the title region gets "dirty" when the
  window lost the focus

### Code simplification

- ~~remove the AGG library in favor of a simple C implementation directly
  using Freetype functions~~ (done)

### Optimizations

- ~directory monitoring to avoid continously rescan. Already well advanced in
  dmon-integration branch but need a new feature from septag/dmon (request done).
- scrolling text optimization. An initial work already done in renchache-texture
  but still incomplete.

## Long term

### Optimizations

- use OpenGL to accelerate rendering.
