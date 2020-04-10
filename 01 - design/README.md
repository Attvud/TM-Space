![cover.img](/01%20-%20design/export/project%20overview/github/cover.png)

Please read the information below carefully. It has everything you and developers need to continue working on this project.

## Download links

- [Source file (.sketch)](Project%20-%20UX,%20UI.sketch). Click on the link and click `"Download"`
- [Animations](/01%20-%20design/animation/)
- [Logotype](/01%20-%20design/export/branding/logotype/README.md)
- [Graphics](/01%20-%20design/export/graphics/)
- [Icons](#icons)

## Help

- Design - [Create a design change request](https://github.com/Attvud/SDS/issues/new/choose) / [Ask a question](mailto:w@res.pm)

## InVision

- Web Site - [Desktop](), [Mobile]()
- Mobile App - [Android]()

InVision is the digital product design platform used to make the world's best customer experiences. Click the link and hold the `"Shift"` button to see the interactive elements.

## Colors

![colors.img](/01%20-%20design/export/project%20overview/github/colors.png)

[Here's the SCSS code](https://github.com/Attvud/SDS/blob/master/X/docs/color%20system.scss) that will create variables for the primary and secondary colors, as well as their shades, and add a palette for grayscale. It is important to use the specified grayscale.

Using this solution, you can easily create a behavior for elements (hover, focus, etc.) and refer to each color and its hue by a variable name.

## Typography

![typography.img](/01%20-%20design/export/project%20overview/github/typography.png)

**Legend**: `R` - Regular, `B` - Bold, `LH` - Line Height. The font set used in the project is marked in blue.

Depending on the platform, you should use the following fonts:

- Web - Arial
- Android - Roboto
- iOS & macOS - SF Pro

**Be sure to use this CSS code in the web front-end**

```css
body {
  font-family: "-apple-system", BlinkMacSystemFont, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
```

## Icons

All icons are optimized using the [SVGO](https://github.com/svg/svgo) API. The weight of the icons was reduced by 30-48%. Export settings are specified in [this file](https://github.com/Attvud/SDS/blob/master/X/docs/svgo.json).

Icons have been successfully tested on the following platforms: Web, Android, iOS.

**All icons are divided into sections**

### Main

![Icons - Main.img](/01%20-%20design/export/project%20overview/github/icons%20-%20main.png)


In this folder, icons are sorted by type - Outlined, Rounded, Sharp. I always use only one icon type per project. You can download icons separately in the following formats: PDF, SVG. All icon types are also available as fonts in the following formats: EOT, TTF, and WOFF.

- [PDF](https://github.com/Attvud/SDS/tree/master/icons/main/rounded/pdf) / [SVG](https://github.com/Attvud/SDS/tree/master/icons/main/rounded/svg) / [Font](https://github.com/Attvud/SDS/tree/master/icons/main/rounded/Icon-Font-Rounded.zip) - Rounded
- [PDF](https://github.com/Attvud/SDS/tree/master/icons/main/outlined/pdf) / [SVG](https://github.com/Attvud/SDS/tree/master/icons/main/outlined/svg) / [Font](https://github.com/Attvud/SDS/tree/master/icons/main/outlined/Icon-Font-Outlined.zip) - Outlined
- [PDF](https://github.com/Attvud/SDS/tree/master/icons/main/sharp/pdf) / [SVG](https://github.com/Attvud/SDS/tree/master/icons/main/sharp/svg) / [Font](https://github.com/Attvud/SDS/tree/master/icons/main/sharp/Icon-Font-Sharp.zip) - Sharp

## Technologies and software used

**UX/UI Design**

- Sitis Design System (SDS) - Design System for this project
- Sketch - UX/UI & Prototyping
- InVision, YouTube – Demonstration of the result of work
- Principle, Flinto, InVision Studio – Animation
- Affinity Designer, Adobe Illustrator – Working with vector graphics
- Affinity Photo, Adobe Photoshop – working with raster graphics
- Github – work with sources, project support, feedback from developers

## Contacts

- UX Designer - Artem Attvud. [Email](mailto:w@res.pm), [LinkedIn](https://www.linkedin.com/in/attvud), [Site](https://res.pm/).
