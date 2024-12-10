# DNHS-darkmode

## ⭐ this repo!

## What this is

This project is a set of css files to add darkmode to certain school sites like MyPlan and Canvas since they don't have a native darkmode of their own. They also introduce some other changes to make the UI much more modern and sleek. However, given that this is not officially supported by these sites, there may be inconsistencies and things may break after some time. Also, some menus may not have a darkmode option because I never use them (although you are free to make a pull request to add the changes in).

## How to use

1. Install [Stylus](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) extension. The link is for the Firefox Add-ons store, but the extension may be available on other browsers.
2. Open the extension.
3. Click "Write new style as UserCSS"
4. Paste the CSS in.
5. Click save.
6. Open "Style settings" and set the "Dark/Light mode preference" to "dark." This makes sure the dark mode theme automatically applies when your computer enters dark mode.
   1. You can also set the preference to "None" so that dark mode is always on.

Notes: for the MyPlan dark mode, you can choose your own profile picture. It's currently set to the one that I use personally but it can be changed. To do this, simply convert your image to a Base 64 encoding (there are converters available online) and paste that in the CSS where my profile picture is.

## File explanations:

- canvas.css: turns Canvas into darkmode
- myplan-login.css: adds a refreshed login page to MyPlan
- myplan-profile-pic-only.css: lets you upload a custom profile picture to MyPlan since PUSD doesn't let you (only shows up on your computer though)
- myplan.css: turns MyPlan into darkmode (also comes with the custom profile picture option)
