usky.googlefont
===============

Google Font editor for Umbraco

uSkyGoogleFont is a property editor that allows you to easily select and add Google fonts to your website.
It allows you to create several blocks of font styles for different html tags. Each style has the following properties:

- Font size
- Font family (google font and regular font)
- Font variant and weight
- Font Color
- Font Line Height

How to install
==============

1. Install the uSky.GoogleFont package in your Umbraco 7 instance
2. Create a new uSky.GoogleFont dataType
3. Add a new property of type uSky.GoogleFont to a Document Type. By default uSkySlider looks for a property called “googleFont”.
4. In the <head> section of your template render the uSkyGoogleFont.cshtml partial view with Html.Partial(“uSkyGoogleFont”)



