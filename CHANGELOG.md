# Changelog

## [0.1.0] - 2026-11-02

The first release.

### Added

- **Basis LTCGI Video Adapter**, which feeds a Basis Media Player's picture into LTCGI's video input, drawn with the
  screen output's flips, projection and placeholder, so a dynamic LTCGI screen lights the room with what the player
  shows.
- **Source Rects**, so the light can come from the part of the frame a screen shows, or from several parts packed into
  one texture (laid out by **Columns**) to light a screen made of several flat panels.
- **Layouts** and the **Layout** property, to switch between sets of Source Rects while the world runs, for a screen
  whose mesh swaps between UV layouts. A uGUI Dropdown can drive it.
- **Basis → Tools → LTCGI → Set Up Video Light On Selected Player**, which adds the controller, the screen and the
  adapter to a media player and bakes, in one undoable step.
