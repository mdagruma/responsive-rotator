# Responsive Rotator

This is a fully responsive, jQuery rotator/carousel. Features include:

* The ability to **toggle auto-rotation** and **set the rotation interval**
* The ability to choose between a traditional **"slide"** or **"fade"** effect
* The ability to choose which slide the rotator starts on
* The ability to have the rotator begin on a random slide on load
* **Auto-height resize** as the rotator images respond
* Touch/device events

## Files Needed

I've put up a sample rotator that includes the recommended HTML structure along with some CSS (along with media queries), though items can be moved around as you see fit. If you want something that's ready-to-roll with limited adjustments, please make sure you use the following:

1. index.html
2. style-rotator.css (load this separately or add it into your project)
3. style-webfonts.css (only if you want the Lato font and/or arrow icons)
4. responsive-rotator.js

## Specific Usage Notes

1. The rotator needs **at least three slides** to function properly. This was purposely done as a rotator likely isn't the functional solution you need if you have fewer slides.

2. **I wouldn't recommend using images wider than 1920px.** I've found this to be the widest statistically-relevant screen resolution. The image height used is 550px. If you need to use shorter images, or require some fixed heights, a CSS solution to handle this is included at the **600px breakpoint.**

3. The indicator HTML is built within the JS. Feel free to edit it as needed.

## Future Releases

1. I've typically used this rotator in standalone situations, though it works nicely within WordPress in combination with Advanced Custom Fields (if you're looking to enhance editing capabilities). I'll be uploading a PHP setup example.

2. The rotator can be easily integrated into other backend systems with UI setup to output specific XML fields. I'll upload a version of the rotator script along with a sample XML document to show this.
