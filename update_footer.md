# How to Update the Footer

Okay, so the footer is a bit of a nightmare, full disclosure. Any other suggestions for this section would be WELCOME.

Here's a pic of the footer:

![Screenshot identifying the footer](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_footer_screenshots/footer_identification.png "Footer identification")

## How to Best Mess With the Footer:

Navigate to the [WP Admin page for the website](http://www.steelcityrollerderby.org/home/wp-admin/) and click the button at the top that says `Steel City Roller Derby`.

![Screenshot identifying how to get to the main site](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_footer_screenshots/main_site_navigation_information.png "Main site navigation identification")

Once you click it, you'll be taken to the main site. You should see a black bar at the top of the screen that says `Steel City Roller Derby` and `Customize`. Click the `Customize` button. You'll see a sidebar that looks like the picture below. Click the `Widgets` button.

![Screenshot identifying the widget button](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_footer_screenshots/widget_button_identification.png "Widget button identification")

Once you click `Widgets`, you'll see a list of all of the widgets that are on the front page. There are 4 separate widgets that make up the footer. Hopefully, this will change, but right now it's what we've got.

![Screenshot identifying the footer widgets](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_footer_screenshots/footer_widgets_identification.png "Footer widgets identification")

If you open up one of them, you'll see that there's a ton of custom HTML. It's a little hard to read. Look at the graphic below for a breakdown.

![Screenshot explaining the footer header](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_footer_screenshots/sponsors_header_identification.png "Footer header explanation")

![Screenshot explaining the image HTML](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_footer_screenshots/image_html_explanation.png "Image HTML explanation")

I **STRONGLY** recommend just copying and pasting this HTML block:
```
<a href="PUT THE LINK THAT YOU WANT THE IMAGE CONNECTED WITH HERE, BETWEEN THE QUOTES"><img class="alignnone wp-image-3766" alt="Horizontal_CMYK_wTime_wContact" src="PUT THE LINK TO THE ACTUAL IMAGE HERE, BETWEEN THE QUOTES" width="160" height="160" /></a><br/>
```

Replace `PUT THE LINK THAT YOU WANT THE IMAGE CONNECTED WITH HERE, BETWEEN THE QUOTES` with the website where you want the image to link to.

Replace `PUT THE LINK TO THE ACTUAL IMAGE HERE, BETWEEN THE QUOTES` with the link to the actual image (easiest is to upload it to the SCRD media library and link directly there). 

Honestly, don't mess with this area unless you have to and try to just copy and paste. If you mess it up and can't get it to look good again, you can remove all of those footer widgets temporarily so that the messed up code isn't seen on the site.

You should be able to see all of the changes that you made preview with a slight delay after you actually make the change.

When you are happy with what you're seeing, click the blue `Publish` button at the top of the `Customize` sidebar.

![Screenshot identifying the publish button](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_footer_screenshots/publish_button_identification.png "Publish button identification")
