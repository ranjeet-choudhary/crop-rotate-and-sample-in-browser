Image manipulation within the Browser
=================================

Library for rotating, cropping, and resizing images within browser.

- Use hermite sampling to resize image for better quality than drawImage. See [this stackoverflow](http://stackoverflow.com/questions/18922880/html5-canvas-resize-downscale-image-high-quality/19223362#19223362)
- Parses EXIF to always provide the correct orientation. See [this article](http://www.daveperrett.com/articles/2012/07/28/exif-orientation-handling-is-a-ghetto/).
- Ability to upload directly to Google Cloud Storage with [Signed URLs](https://developers.google.com/storage/docs/accesscontrol#Signed-URLs).
