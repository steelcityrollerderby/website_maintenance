# How to Update the Sidebar:

![Screenshot identifying the sidebar](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_sidebar_screenshots/sidebar_identification.png "Sidebar identification")

1. Navigate to the [wp-admin version of the website](http://www.steelcityrollerderby.org/home/wp-admin) and log in.

2. Navigate to [widgets](http://www.steelcityrollerderby.org/home/wp-admin/widgets.php) or click on `Appearance` in the left sidebar and then click on `Widgets`. You're going to be updating the part of the site that says `Sidebar`.

![Screenshot showing you how to get to widgets](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_sidebar_screenshots/how_to_navigate_to_sidebar.png "How to Navigate to Widgets")

3. To edit the sidebar part of the website, click on the arrow next to `Sidebar`. Then, click on the arrow next to `Upcoming!`. You're going to see some basic HTML. Feel free to add whatever styling you want as long as it's legible and it looks good. Please don't edit anything below the line that says `<!-- Begin MailChimp Signup Form -->` because it's all setup right now aaaaaand it's annoying to try to fix it. If you decide to edit below there because you have awesome ideas of how to make it better, just copy/paste the code that's in there into a text document so that you can put it back if something you edit breaks.

![Screenshot showing you where you're going to be editing](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_sidebar_screenshots/open_edit_sidebar_section.png "Navigate to Upcoming!")

4. Edit away. The most important thing to put in the sidebar are our upcoming events, especially bouts. We also want to make sure that we're putting the ticket link in the sidebar as well. Some basic HTML tips:
  - Put anything you want **bold** in `<strong>` tags, like this: `<strong>WHATEVER YOU WANT</strong>`
  - Add a link like this: `<a href="https://whateveryouwant.com">THE TEXT THAT YOU WANT TO SHOW UP</a>`
  - Add a line break like this: `<br>`. You can do multiple of these to add multiple lines.

Here's an example of code that I've used:
```
<strong>LOOKING TO JOIN STEEL CITY ROLLER DERBY???????</strong><br>
Pre-tryout Bootcamps!!!!<br>

<a href="https://www.brownpapertickets.com/event/3572044">Monday September 10th</a><br>

<a href="https://www.brownpapertickets.com/event/3572046">Monday September 17th</a><br>

<br><strong>Tryouts will be Sept 24.</strong> <br>Stay tuned for times and ticket link!!
<br><br>
```

And here's what it looks like on the website:

![Screenshot of an example sidebar](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_sidebar_screenshots/example_sidebar.png "Example sidebar")

5. When you're done, click save and then navigate to the [regular website](https://steelcityrollerderby.org) to check how it looks. If you don't like it, go back to the widget and continue to edit. If you don't see your changes, try refreshing the page. If you still don't see your changes, clear your cookies.

![Screenshot identifying the save button](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_sidebar_screenshots/save_button_identication.png "Save button")


**Note:**
Another option is to edit the widgets using the `Customize` option. Go to the sidebar on the left and click `Appearance`. Then, click `Customize` as show below. You could also navigate directly [here](http://www.steelcityrollerderby.org/home/wp-admin/customize.php?return=%2Fhome%2Fwp-admin%2Fwidgets.php).

![Screenshot identifying where customize is](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_sidebar_screenshots/show_where_customize_is.png "Customize identification")

You'll see something like this:

![Screenshot showing what customize looks like](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_sidebar_screenshots/customize_example.png "Customize example")

Click `Widgets`. 
Click `Sidebar`.
Click the arrow next to `Upcoming!` to expand it and you'll see this.

![Screenshot showing where to edit code in the customize view](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_sidebar_screenshots/customize_sidebar_detail.png "Customize detail")

Then, edit everything as described above.
