Shopify Carousel
======
A simple Carousel for Shopify platforms. Utilizing
[Slick](https://github.com/kenwheeler/slick/) to run the carousel.

SCSS is seperated into its own sheet, but you will be better off trying to add
the SCSS to your existing sheet to save space.

If you are using Slate I would suggest modularizing the classes to your desire.

Setup
------
Simply copy `sections/carousel.liquid` into your themes `sections` directory,
and add the contents of `assets/carousel.scss` to your existing stylesheets.

Then head over to [Slicks](https://github.com/kenwheeler/slick/) repo and 
install the Javascript onto your theme.

Finally customize to your hearts content. The carousel makes some assumptions
about how your classes are setup so take the time to setup how you see fit.

###Expected Classes
The following classes are expected to already be defined in your stylesheets.

| Class       | Use                                                                               |
| ----------- | --------------------------------------------------------------------------------- |
| .btn        | Basic button styling as per your theme.                                           |
| .btn-custom | Specifically the custom button type, useful for Bootstrap                         |
| h1-h6       | All typography, particularly headings, are exected to be styled                   |
| .title      | While this is styled in the carousel.scss, I suggest styling to match your theme. |

###Included Classes
The carousel comes with a few useful classes that you may want to reuse in your
theme to save on double-dipping, and to avoid bloating.

| Class        | Use                                                                                                                                   |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------- |
| .box-sizer   | A simple div that will keep a defined aspect ratio no matter the width of its parent. Good alternative than using an img to do this.  |
| .content-box | A floating div of contents, great for when you want to put some stuff ontop of an image and have it size nicely on responsive devices |

### TODO
Not much at this moment, I wouldn't mind improving the Theme Editor logic since it's a bit iffy, and also the Content Box is not ideal but works for now.

Any requests feel free to contact or raise an issue, happy coding!