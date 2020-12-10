---
title: Laser Cutter
description: A guide on how to use the laser cutter.
published: true
date: 2020-12-10T20:26:35.831Z
tags: fabrication, guide
editor: markdown
dateCreated: 2020-03-13T15:57:43.084Z
---

> This page is a work in progress. Information may be missing or incomplete.
{.is-warning}

# Laser Cutter

[comment]: # (this is a comment which will not be rendered into the final document)
The laser cutter uses a laser to  into flat surfaces of soft materials like wood, acrylic, and leather. Designs can be uploaded to it to control what it cuts. It can also engrave and score material.

## Overview
This is a top-down view of the laser cutter.

![glowforge_diagram.png](/laser_cutter/glowforge_diagram.png)

The laser is produced in the laser tube and then reflected with mirrors to the laser head. The laser head's position is controlled by motors on either side allowing it to cut anywhere on the bed. Smoke is exhausted out the vent with fans inside the machine which is where a majority of the noise comes from during use.

## Creating a Design
Designs for the laser cutter come in a number of forms but the most common (and accurate!) is an SVG or Scalable Vector Graphics file. These end in `.svg` and can be found online or created with compatible programs such as [Adobe Illustrator](https://www.adobe.com/products/illustrator.html) or [Inkscape](https://inkscape.org/). This guide won't cover how to use these programs but you can find tutorials online or ask someone who does know. 
## Uploading and placing a Design
> In order to use the laser cutter you will need a [Glowforge account](https://app.glowforge.com/). If you don't have an account [contact Case](mailto://case.norris@sdsgriffin.org) to get one set up.
{.is-info}

Once you are logged into glowforge you should see a screen like this:

![glowforge_home.png](/laser_cutter/glowforge_home.png){.elevation-3 .radius-5}

This is the home screen. It has all of the designs you have uploaded in the past as well as some ones included by default. Go ahead and click create. It should prompt you with a few options. 

![create_new_design_prompt.png](/laser_cutter/create_new_design_prompt.png)

You can upload new designs at any time from within their menu so don't worry too much about which one to choose right now. If you don't already have a design downloaded, just click *New blank design*. You should be greeted with this screen.

![design_screen_overview.png](/laser_cutter/design_screen_overview.png)

If it seems confusing right now, that's alright it should make a lot more sense in just a bit.

![design_screen_overview-camera_view.png](/laser_cutter/design_screen_overview-camera_view.png)

The highlighted area is the camera view. It displays what the camera at the top of the laser cutter sees inside the machine. In this case there is nothing, but anything you put inside the machine should appear on this screen after closing the lid.

The blue plus button on the top middle of the screen is how you add new designs. When you click on it you should see something like this. 

![add_design_button_prompt.png](/laser_cutter/add_design_button_prompt.png){.align-center .radius-5}

The most important button here is the upload button on the top right of this dialog. It allows you to upload any design you've made or any pictures you've found online. If you're wondering what kind of files you can upload, click [here](https://glowforge.com/faq/design#which-design-platforms-does-glowforge-work-with). While it's possible to upload just about any picture or design you can find, note that not all of them will print well or give you the result you might want. Files that "print well" typically have clear outlines and not many filled in areas. You can find a guide on identifying easily printable files online [here](/en/refrences/printable-files).

After uploading or placing a design it will appear inside the editor. You can drag the design around to control where it will be cut and control the size of it by dragging one of the corners.

[[picture of editor with design inside]]

On the left side of the screen is is a list of all designs (or parts of single designs) you have uploaded.

![left_side.png](/laser_cutter/left_side.png){.align-center .radius-5}

Designs can be cut, engraved, scored, or ignored:
1. Cutting will cut all the way through the material. Doing this all the way around a design will allow you to remove it from the rest of the material. Cutting a design requires that it be a path and not simply a picture. [[picture of something that was cut]]
2. Engraving will burn a shallow imprint of the design into the material. This can be used to cut out pictures or any other solidly filled design. This does not require a path. [[picture of something that was engraved]]
3. Scoring will burn deeper into the material than engraving. This is good for text and things that are supposed to be more defined than an engraving will give you. This requires a path. [[picture of somehthing that was scored]]
4. Ignoring a design will prevent from being it cut at all. This is useful for for taking certain objects out of a design when testing. This can be done to any design.

![cut_options.png](/laser_cutter/cut_options.png =75%x){.align-center .radius-5}

These settings can be controlled by clicking on your design on the left panel and selecting one of these options at the top of the dialog. 

![design_option_panel.png](/laser_cutter/design_option_panel.png){.align-center .radius-5}