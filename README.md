<img width="1920" height="1080" alt="post" src="https://github.com/user-attachments/assets/765b9a1f-b59b-4681-a642-35114ff9bd59" />

# WallpaperPackageUnpacker

WallpaperPackageUnpacker is a tool for parsing Wallpaper Engine `.pkg` and `.mpkg` packages, reconstructing internal resources, and exporting images, videos, textures, materials, masks, shaders, and scene data.

## Features

* Parse `.pkg` and `.mpkg` files
* Restore the original resource directory structure
* Extract textures, materials, masks, effects, shaders, and media files
* Convert TEX images to standard image formats
* Export static images and MP4 videos
* Reconstruct selected region-based animation effects
* Support drag-and-drop file import
* Display real-time progress and task logs

## Default Output Location

Extracted files are saved to:

```text
Downloads/WallpaperPackageUnpackerOutputFile/
```

Each task creates a separate timestamped directory:

```text
YYYY-MM-DD_HH-MM-SS/
```

Exported media files are stored in:

```text
mediadata-[package-name]/
```

The output root directory can be changed in Preferences.

## Supported Formats

```text
.pkg
.mpkg
```

## Usage

1. Launch WallpaperPackageUnpacker.
2. Select the PKG or MPKG mode.
3. Drag a package into the application or select it manually.
4. Start the extraction process.
5. Open the output directory after the task is complete.
6. Configure media export settings when image or video output is required.

## Project

Project homepage:

```text
https://github.com/LinyeXie
```

## License

This software is proprietary.

Copyright © 2026 Linye Xie. All rights reserved.

Unauthorized copying, modification, redistribution, reverse engineering, or commercial use of this software is prohibited without prior written permission.
