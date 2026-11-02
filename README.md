# Cosmic Scale

An interactive tour of size: from planets and their moons, through the stars and nebulae of the Milky Way, out to the cosmic web and the edge of the observable universe.

<p align="center">
  <a href="https://allenvincent808.github.io/cosmic-scale/"><img alt="Launch Cosmic Scale" src="https://img.shields.io/badge/%F0%9F%9A%80_Launch_Cosmic_Scale-open_in_your_browser-ffc96b?style=for-the-badge&labelColor=0c0e1a"></a>
</p>

<p align="center"><b>▶ <a href="https://allenvincent808.github.io/cosmic-scale/">allenvincent808.github.io/cosmic-scale</a></b><br>
<sub>Works on desktop and mobile · no install needed</sub></p>

## Features

- **Solar System**: planets and moons in their real positions for any date, with real rotation periods and tilts, plus **509 real asteroids, comets and dwarf planets** on their catalogued orbits
- **One continuous zoom**: fly from the Sun past the Oort cloud and the nearest stars to the whole Milky Way and beyond, using the mouse wheel, the scale ruler or the speed slider
- **Milky Way from real catalogues**: 109,400 stars, 6,476 open clusters, 196 globular clusters, 4,253 pulsars, named stars and nebulae
- **Universe from real catalogues**: 10,936 galaxies with measured distances, and every Local Group member in McConnachie's catalogue
- **Everyday scale**: shrink Earth to a peppercorn, a marble or a basketball and see how big and how far away everything else becomes

## What is illustrative

Almost everything is drawn from catalogues. Three things can't be, and each can be switched off in the app:
- the **Oort cloud**, which has never been observed directly
- the **spiral-arm model** of the whole galaxy, because no survey maps the far side of the Milky Way
- the **distant cosmic web** beyond about 1.5 billion light-years

## Credits

Created by **Allen Vincent**.

Built in collaboration with **Claude**, an AI model by [Anthropic](https://www.anthropic.com). Allen came up with the concept, set the direction and features, and reviewed each version. Claude wrote the code and helped research, assemble and cross-check the scientific data.

### Data sources (full list in the app under ⓘ About)
- NASA Planetary Fact Sheet; JPL Solar System Dynamics (planet and moon orbits); the IAU (star names)
- HYG Database v4.1 by Astronexus: Hipparcos, Yale and Gliese stars (CC BY-SA 4.0)
- [Celestia](https://github.com/CelestiaProject/CelestiaContent) catalogues: galaxies (Revised NGC/IC by Steinicke 2006, and Karachentsev et al. 2004), globular clusters (Baumgardt et al.), open clusters (Perren et al. 2023, CC BY 4.0), pulsars (ATNF v2.6.3, CC BY 4.0)
- [Stellarium](https://github.com/Stellarium/stellarium) minor-body orbital elements (from the MPC and JPL)
- McConnachie (2012), Local Group; Tully et al. (2014), Laniakea; Planck Collaboration (2020)

## License

Some of the bundled data is GPL-2.0-or-later (Celestia, Stellarium) or CC BY-SA 4.0 (HYG), so this project is shared under the **GNU GPL v3.0**. Each data source's own license and attribution still applies.

## Technical notes

Everything is in a single `index.html` file: a custom WebGL 2 renderer with no third-party libraries and no build step. The embedded catalogue data is about 2.5 MB.
