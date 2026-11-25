# JustComets release notes

What is new in each version of JustComets, newest first. The same notes are in the program's help
(**Documentation**, **Release notes**). The files of every version are on the [releases page](../../releases);
what JustComets does is in [the tour of its features](FEATURES.md).

## 2026.11.0 (beta)

Released on 2026-11-25. The first public release of JustComets.

- **Observation Planner**: finds the comets and asteroids worth observing tonight - typed in, or imported from lists
  of candidates - fetches their ephemerides from the MPC or JPL Horizons, and gives each a block of the night within
  your horizon, the twilight, the Moon and the meridian limits of your mount. The plan can be changed by hand and
  exported for N.I.N.A.'s Advanced Sequencer, KStars/Ekos, CCDCommander and the ZWO ASIAIR (see
  A night of comets for N.I.N.A.).
- **Astrometry and Photometry**: calibrates and plate-solves the frames of a night against Gaia, stacks them on the
  stars or on the moving target, measures positions and magnitudes - with the FoCAs photometry of comets - and
  prepares the report for the Minor Planet Center, in ADES or in 80 columns, with a check of its quality before you
  send it (see Comet astrometry to the MPC).
- **Image Annotation**: adds to a picture of a comet a band with its name, your equipment, the observation from your
  MPC report and the observing geometry, marks the comet, enlarges details of its coma - also with isophotes - and
  exports the JPG (see An annotated comet image).
- **Image Processing**: the whole way from the frames of a night to a finished picture, in nodes that you link and
  can change at any time: calibration, alignment on the stars or on a comet, integration, Drizzle and Mosaic,
  background, color, stretch, curves, noise reduction, deconvolution, masks and Pixel math. **Templates...** starts
  from a ready-made workflow (one-shot color, comet, mono LRGB, narrowband), and **Comet integration** gives the comet
  without the stars and the stars without the comet (see Image Processing basics).
- **For Windows, Linux and macOS**: a setup for Windows 10 and 11, an AppImage for 64-bit PC Linux desktops and a
  disk image for Macs with Apple silicon (see Getting started).
- **In English and Spanish**: the program and its help - the user's manual, the tutorials, the reference of every
  control and the glossary. F1 opens the page about what is under the mouse.
- Questions, bug reports and ideas: info@cieloprofundo.net (see Questions, bug reports and ideas).
