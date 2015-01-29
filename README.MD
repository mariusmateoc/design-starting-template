#### Design Template

This repository have several branches that contain my design starting templates at different resolutions for different devices. So if you want to use this when you start a new project just:

```bash
# Clone this repository
git clone git@github.com:mariusmateoc/design-starting-template.git
# Checkout the specific branch that you want to use from below
git checkout <branch-name>
```

* `branch web` **1200px webpage:** A blanc file at 1400px wide and 1200px tall. This file comes with a default grid system at 1200px wide with 12 columns (Column Width: 78px; Gutter Width: 24px) and a baseline grid of 12px.

* `branch web-old` **1024px webpage:** A blanc file at 1224px wide and 1024px tall used to start new design project. This file comes with a default grid system at 1024px wide with 12 columns.

* `branch iphone` As you can guess an iPhone6 portrait template.

* `branch phone` **320x480** A stating template for smaller phones.

* `branch icon-ios` iPhone and iPad icon templates from [bjango](http://bjango.com/)


**Note!** Do not design your UI for a single resolution, you should design it to be resolution-independent.
You can use the resolution 320x480 that is MDPI as long as you deliver your assets for the app in other DPI sizes:

* LDPI (low): x0.75 the size of your current assets
* MDPI (medium): the size of the assets you are currently using
* HDPI (high): x1.5 the size of current assets
* XHDPI (extra high): x2.00 the size of current assets

The phone OS choose whichever asset is the best for the device.


##### Create your custom grid

* Use [GuideGuide](http://guideguide.me/) to create custom grids
* To calculate your grids use this [Grid Calculator](http://gridulator.com/)
* To change baseline grid download [Vertical Rhythm Patterns](http://blog.kam88.com/en/vertical-rhythm-pattern-pack.html) from Kamil Khadeyev

<!---
For more information and see my workflow visit my blog link.
-->