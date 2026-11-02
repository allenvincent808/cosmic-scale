# Cosmic Scale

**Feel how big, and how empty, space really is.**

Most pictures of space cram the planets side by side and make the sky look crowded. The real universe is unimaginably big and almost completely empty. Cosmic Scale is an interactive tour drawn at true scale from real astronomical catalogues: from the planets and their moons, through the stars and nebulae of the Milky Way, out to the cosmic web and the edge of the observable universe.

<p align="center">
  <a href="https://allenvincent808.github.io/cosmic-scale/"><img alt="Launch Cosmic Scale" src="https://img.shields.io/badge/%F0%9F%9A%80_Launch_Cosmic_Scale-open_in_your_browser-ffc96b?style=for-the-badge&labelColor=0c0e1a"></a>
</p>

<p align="center"><b>▶ <a href="https://allenvincent808.github.io/cosmic-scale/">allenvincent808.github.io/cosmic-scale</a></b><br>
<sub>Works on desktop and mobile · free · no install, no account</sub></p>

## Features

- **True scale from the first second**: the Solar System opens with its real sizes and distances. The planets are far smaller than a pixel, so the dots only mark where they are. *Readable* mode, one tap away, shows the squeezed textbook version.
- **One continuous zoom**: fly from the Sun past the Oort Cloud and the nearest stars to the whole Milky Way and beyond, using the mouse wheel, the scale ruler or the speed slider. You can also try **⚡ Auto-tour**.
- **Solar System**: planets and moons in their real positions for any date, with real rotation periods and tilts, plus **509 real asteroids, comets and dwarf planets** on their catalogued orbits. Voyager 1 and 2 move outward over time.
- **Milky Way from real catalogues**: 109,400 stars, 6,476 open clusters, 196 globular clusters, 4,253 pulsars, named stars and nebulae.
- **Universe from real catalogues**: 10,936 galaxies with measured distances, and every Local Group member in McConnachie's catalogue.
- **🍊 Everyday scale**: shrink Earth to a peppercorn, a marble or a basketball and see how big and how far away everything else becomes.
- **📸 Share a postcard**: turn whatever you're looking at into an image with a human-scale fact, such as *"If the Sun were a basketball, Neptune would be a pea about 775 metres away."*

## 🎮 Play & Discover

- **🎂 Your Birthday Sky**: enter when and where you were born and see the real sky above that place at that moment. You can look around inside the dome, switch to a round sky map, or **unflatten the sky** to watch each star fly out to its true distance. Tap any star to see how many years before your birth its light set out. Then see how far your own "birthday light" has travelled since.
- **📏 Guess the Scale**: ten slider questions, each with a fly-there view.
- **🎯 Space Darts**: throw darts at random into the Solar System and try to hit *anything*.
- **📨 Cosmic Mail**: send a light-speed message to the Moon, Mars, Voyager 1, Proxima b or Andromeda, and see when it arrives.
- **🏠 The Universe in Your Town**: put a model Sun in your town (searchable list of 7,280 cities) and see where the planets, Voyager and the nearest star would land.
- **🏅 Space Hunt**: 16 missions and badges for kids.

## 🔒 Privacy

Cosmic Scale has no server, no account, no cookies, no analytics and no tracking. Everything is calculated in your browser:
- Your birth date, time and place are never saved or sent anywhere, and are forgotten when you close the panel or the page.
- "Use my location" is used once on the page and then discarded.
- Postcards are drawn on your device and only leave it if you choose to share them.
- The only thing stored is your Space Hunt badge list, kept in your own browser.

Like any website, GitHub Pages records visits in its server logs, and the fonts are loaded from Google Fonts. Neither ever sees anything you type into the page.

## What is not drawn from a catalogue

Almost everything is drawn from catalogues. Three things can't be, and each can be switched off in the app:
- **The Oort Cloud**: its objects have not been seen directly yet. Its existence is inferred from long-period comets, so the app shows its expected extent.
- **The spiral-arm model of the whole galaxy**: no survey maps the far side of the Milky Way.
- **The distant cosmic web** beyond about 1.5 billion light-years.

## Credits

Created by **Allen Vincent**.

Built in collaboration with **Claude**, an AI model by [Anthropic](https://www.anthropic.com). Allen came up with the concept, set the direction and features, and reviewed each version. Claude wrote the code and helped research, assemble and cross-check the scientific data.

### Data sources (full list in the app under ⓘ About)
- NASA Planetary Fact Sheet; JPL Solar System Dynamics (planet and moon orbits); the IAU (star names); IAU Minor Planet Center and NASA (moon counts, 2026); NASA/JPL (Voyager distances).
- HYG Database v4.1 by Astronexus: Hipparcos, Yale and Gliese stars (CC BY-SA 4.0).
- [Celestia](https://github.com/CelestiaProject/CelestiaContent) catalogues: galaxies (Revised NGC/IC by Steinicke 2006, and Karachentsev et al. 2004), globular clusters (Baumgardt et al.), open clusters (Perren et al. 2023, CC BY 4.0), pulsars (ATNF v2.6.3, CC BY 4.0).
- [Stellarium](https://github.com/Stellarium/stellarium) minor-body orbital elements (from the MPC and JPL).
- [d3-celestial](https://github.com/ofrohn/d3-celestial) by Olaf Frohn: constellation lines and star designations (BSD-3-Clause).
- [city-timezones](https://github.com/kevinroberts/city-timezones) by Kevin Roberts: cities and time zones (MIT).
- Meeus, *Astronomical Algorithms* (precession, sidereal time); *Astronomical Almanac* low-precision Moon formulae.
- McConnachie (2012), Local Group; Tully et al. (2014), Laniakea; Planck Collaboration (2020).

## Accuracy

Birthday Sky has been checked against known events:
- The 2020 Jupiter–Saturn great conjunction (0.1° apart).
- The 8 April 2024 solar eclipse.
- Venus's greatest elongation in March 2020 (46.1°).
- Earth's perihelion distance.

Star positions agree with an independent calculation to within about 0.1°.

Planet positions use mean orbital elements, which are good to a fraction of a degree between 1800 and 2050. The Moon is good to about half a degree.

## License

Some of the bundled data is GPL-2.0-or-later (Celestia, Stellarium) or CC BY-SA 4.0 (HYG), so this project is shared under the **GNU GPL v3.0**. Each data source's own license and attribution still applies.

## Technical notes

Everything is in a single `index.html` file: a custom WebGL 2 renderer with no third-party libraries and no build step. The embedded catalogue, city and sky data is about 3 MB.
