# OBE:BS4 Library Design System

The OBE:BS4 Design System is the world's first self-reflexive design system for web production. OBE:BS4 is based on the most popular/robust front-end web framework in the world, Bootstrap! The OBE:BS4 system was designed & built to give all project stakeholders total visual, technical, and tactile access to every color, font, element, component and layout in a web project... *before the project enters any design phases!*

THE OBE:BS4 Design System was designed to bridge the gaps between web project owners, designers, and developers. OBE:BS4 achieves this goal by fostering a more healthy understanding of both code and design *constraints* in the context of the final output medium(s)... the web browsers!

> **Please Note:** *This project is fully functional as far as the generated CSS, JS, and library HTML files are concerned. However it will receive some _substantial changes_ before being ready for all to use. Keep an eye on this page, to learn more about how everything works as documentation is added!*


---


## Table of Contents

* [About](#about)
    * [Project Structure](#project-structure)
    * [Project Color Wheel](#project-color-wheel)
    * [Project Build Tooling](#project-build-tooling)
* [Installation](#installation)
    * [Installing with NPM](#installing-with-npm)
    * [Installing with Zip](#installing-with-zip)
* [Roadmap](#roadmap)


---


## About

The OBE:BS4 Design System is meant to nudge projects, teams, and even entire organizations towards making both strategic and design related decisions about their project *exclusively within* the contexts of the browsers. This approach has tremendous value, especially with common responsive design issues!

So in a sense, this system was made to eventually replace design-centeic tooling that insists on "never writing a line of code." Instead, OBE:BS4 doesn't assume designers are incapable of learning about *markup* or copy/pasting HTML snippets. So this design system arms designers with both visual and markup examples of anything/everything a designer might need to use in a design situation.

> *"OBE:BS4 assumes that everyone working on a web project needs transparent access to each option and limitation of the project at all times."* - Matt McT

Accomplishing this was done through a surprisingly simple operational tweak. The secret, was creating a system where the front-end specialists are required to provide the design specialists a complete reference of design element options, already cross-browser optimized, and and accessible from any device, all before **_any_** design work begins.

This change forces front-end specialists to strategically plan ahead for their eventual handoff. What's magical about this process is that it gives front-end specialists the unheard of opportunity to refactor and templatize elements/components at a production level, before **_any_** design sprints even kickoff!

The OBE:BS4 Design System forces **_all_** project stakeholders to think more strategically about *responsive* content issues, by abstracting every single design aspect to solve those issues into a giant digital box of designer-ready pieces. If each piece is in-turn fully optimized for production (IE valid, semantic, cross-browser, accessibile, and optimized for reuse), then the entire production line now has the cognative room to focus on what the web is really all about... facilitating user content consumption, fostering eCommerce conversions, and/or offering high-quality and accessible services... on any device.

### Project Structure

(Coming Soon!)

### Project Color Wheel

To work with the OBE:BS4 Design System, it is imperative that you understand the system's "color Wheel." Before we dive into that though, let's cover why a color wheel was necessary to begin with.

Long story short, the color "contextual" classes popularized by Bootstrap (primary, secondary, danger, etc.) were combined with the Google Material Design color guidelines. Next branding was factored in, including seasonal "off-brand" collateral across both digital and analog mediums. To organize all of that complexity for any given poject, and to provide contingency color options outside of the core brand colors for both digital and analog design edge cases, the color wheel system emerged.

You'll want to use the wheel to integrate any current branding into the OBE:BS4 system. Then by using the Design System's built-in settings tool (Example: [OBE:BS4 Settings Page](https://library.mattmct.com/settings.html)), you can specify your settings, grab the generated JSON, replace your existing settings file JSON with your new data, and finally re-generate your library site to integrate your settings in seconds!

Your team now has a complete reference for web site/app design options, and each option is "on-brand" visually as well as ready for production use. This magic all starts with the color wheel!

#### List of Color Wheel Colors

PRO TIP: If possible, try to memorize these! Knowing these by memory will let you iterate VERY rapidly!

| Name | CSS Slug | JS Slug |
| --- | --- | --- |
| Red | red | red |
| Rose | rose | rose |
| Magenta | magenta | magenta |
| Violet | violet | violet |
| Blue | blue | blue |
| Azure | azure | azure |
| Cyan | cyan | cyan |
| Spring Green | spring-green | springGreen |
| Green | green | green |
| Chartreuse | chartreuse | chartreuse |
| Yellow | yellow | yellow |
| Orange | orange | orange |
| Orange Gray | orange-gray | orangeGray |
| Dark Gray Orange | dark-gray-orange | darkGrayOrange |
| Blue Gray | blue-gray | blueGray |
| Light Gray Azure | light-gray-azure | lightGrayAzure |
| White | white | white |
| Light Gray | light-gray | lightGray |
| Gray | gray | gray |
| Dark Gray | dark-gray | darkGray |
| Black | black | black |

#### Example of Color Tints and Shades

PRO TIP: When using the Design System's tints and shades, each color gets a set of tint and shade values like the example for Blue below. Also and for all color options with tints and shades, using the color slug without any numbers is equal to the 500 variation of that color. So for example, "Blue" is equal to "Blue 500" and so fourth!

| Name | CSS Slug | JS Slug |
| --- | --- | --- |
| Blue 50 | blue-50 | blue50 |
| Blue 100 | blue-100 | blue100 |
| Blue 200 | blue-200 | blue200 |
| Blue 300 | blue-300 | blue300 |
| Blue 400 | blue-400 | blue400 |
| Blue | blue | blue |
| Blue 500 | blue-500 | blue500 |
| Blue 600 | blue-600 | blue600 |
| Blue 700 | blue-700 | blue700 |
| Blue 800 | blue-800 | blue800 |
| Blue 900 | blue-900 | blue900 |

### Project Build Tooling

(Coming Soon!)


---


## Installation

There are two basic ways to install the OBE:BS4 Design System. One method is to use Node.js/NPM to install the project as a node module from your console. The other way is to 'old school' download the project zip from here on GitHub, and then copying any necessary extracted files/directories into your project's root folder.

To really start using your Design System however, you'll need to somehow use an OBE:BS4 Settings Tool page to get the JSON settings to customize your Design System. (Coversely you could also get your JSON settings from the project's offical example [OBE:BS4 Settings Page](https://library.mattmct.com/settings.html)).

Then you'll need to use Gulp to run the scripts needed to apply your settings and re-generate the HTML, CSS, and JS files for your library. Then you are ready to use your Design System to make amazing web stuff!

*NOTE: This project uses Gulp to manage and generate the Design System Library Site. So if you are already using Gulp, be sure to not override your gulpfile.js file with the OBE:BS4 gulpfile!*

### Installing with NPM

**Step 1**: Create a directory for your project, navigate to it in your console, nitialize NPM, and fill out your project info for your package.json file as prompted by NPM.
```bash
npm init
```

**Step 2**: Install obebs4-design-system from GitHub (NPM will install all dependencies and this codebase inside the 'node_modules' directory)
```bash
npm install --save oberocks/obebs4-design-system#master
```

<!---
**Step 3**: Use the following series of command line scripts to move the starting library files into your working directory
```bash
npm run create-obebs4-directories
```
-->

### Installing with Zip

(Coming Soon!)


---


### Roadmap

(Coming Soon!)
