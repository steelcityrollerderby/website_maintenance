# How to Update the Team Pages

This is the hardest area to maintain, partly because you likely won't get all of the pictures at the same time and partly because the pictures aren't the same size. Here's a strategy that worked for me. If you've got a better one, DEFINITELY use that.

## Team Pages:

There are three team pages ([Steel Hurtin'](http://www.steelcityrollerderby.org/home/teams/steel-hurtin/), [Steel Beamers'](http://www.steelcityrollerderby.org/home/teams/steel-beamers/), and the [Blitzburgh Bombers](http://www.steelcityrollerderby.org/home/teams/blitzburgh-bombers/)).

### Steel Hurtin' Team Page Structure

- Skaters
- Staff

### Steel Beamers Team Page Structure

- Skaters
- Staff

### Blitzburgh Bombers Team Page Structure

- Permanent Members (people who's only team is the Bombers)
- Featured Skaters (people who skate for the Bombers occasionally but are on other teams)
- Staff

## Create Envira Galleries for Each Section of Each Team

The easiest way to get the pics on the website of the skaters and staff is to create an Envira gallery for each section (for example, the Bombers have 3 Envira galleries: Permanent Members, Featured Skaters, and Staff).

To create a new Envira gallery, click the `Envira Gallery` button on the left sidebar. Then, click the `Add New` button in the middle of the screen. 

![Screenshot how to navigate to a new envira gallery](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_team_pages_screenshots/envira_gallery_identification.png "New envira gallery identification")

You should see the page in the screenshot below.
 
Add a title. The title should be the format `TEAM NAME` `YEAR` `HEADSHOTS or STAFF`. Where `TEAM` is Hurtin, Beamers, or Bombers and you choose HEADSHOTS for the skater galleries and STAFF if they're staff.

Once you've got a title, go ahead and upload the images from your computer (the `Select Files from Your Computer` button) or choose them from the Media Library if they're already uploaded to the site (the `Select Files from Other Sources` button).

![Screenshot how to setup a new envira gallery](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_team_pages_screenshots/make_new_envira_gallery.png "Setup envira gallery identification")

After all of the images that you currently have are updated, you need to edit their metadata. Click on the small blue pencil button of any image to start editing.

![Screenshot of the metadata edit button](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_team_pages_screenshots/edit_image_metadata_button.png "Metadata edit button identification")

You should see a large popup of the individual image that you clicked.

1. Edit the `Title`. The `Title` is what is going to show up when an image is hovered over on the site. This should be in the format `SKATER-NAME` `#NUMBER` and `Captain` or `Co-captain` if relevant. `SKATER-NAME` should be the skater's full name (for example, Wolverkween tends to go by Kween, but her full name should be on the site).
Example: `Wolverkween #106` (Wolverkween is not a Captain so there is nothing else in the title).

2. Edit the `Alt-Text` so that it is in the format `SKATER-NAME` `NUMBER` `Headshot - ` `TEAM` `YEAR`
Example: `Wolverkween 106 Headshot - Bombers 2018`

3. Click `Save Metadata` when you're done.

4. Then, click the arrow at the top right of the popup to move to the next picture in the gallery. Continue until you've edited the metadata of every image in the gallery.

![Screenshot of the edit metadata details](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_team_pages_screenshots/metadata_editing_details.png "Edit metadata details identification")

## Put the Envira Gallery on the Team Page

Once you've got an Envira gallery created for a team, go to the relevant team page (listed below).

[Hurtin'](http://www.steelcityrollerderby.org/home/wp-admin/post.php?post=23&action=edit)
[Beamers](http://www.steelcityrollerderby.org/home/wp-admin/post.php?post=3469&action=edit)
[Bombers](http://www.steelcityrollerderby.org/home/wp-admin/post.php?post=25&action=edit)

Delete any galleries that are currently there, but try not to delete the titles (highlight the entire thing to see the titles). Click on the button that says `Add Gallery` with a little green leaf next to it. 

![Screenshot of the edit team page screen with add gallery button identified](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_team_pages_screenshots/identify_add_gallery_button.png "Add gallery button identification")

This should take you to the following popup. Choose one of the galleries. Make sure that `Display Title` is `No`. Then, click the blue `Insert` button at the bottom right of the page). Note that the gallery will be inserted wherever your cursor currently is.

![Screenshot of choose a gallery popup](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_team_pages_screenshots/inserting_a_gallery.png "Choose gallery popup identification")

Once you've got the gallery inserted (it will just look something like this `[envira-gallery id="6526"]` on the Edit page), navigate to the `Text` tab. Highlight the entire thing to make sure that there are titles. If there isn't a title for the gallery, navigate to the Text tab as shown below.

![Screenshot identifying the Text tab](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_team_pages_screenshots/navigate_to_code_editing.png "Text tab identification")

Make sure that there is a title above each insert of the gallery.

A gallery insert looks like this:
`<p style="text-align: center;">[envira-gallery id="6526"]</a></p>`

You should make sure that this line
`<p style="text-align: center; color: white;"><strong>TITLE OF GALLERY</strong></p>` is above each envira gallery insert (where `TITLE OF GALLERY` should be replaced with `Skaters`, `Staff`, `Permanent Members`, or `Featured Skaters` depending on what team/gallery you're working with).

![Screenshot how to add titles](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_team_pages_screenshots/adding_a_title_to_the_gallery.png "Title explanation")


Go to the `Publish` box on the right and preview your changes by hitting the `Preview` button. If you are satisfied, click the blue `Update` button.

![Screenshot identifying the Preview and publish options](https://github.com/steelcityrollerderby/website_maintenance/blob/master/screenshots/update_team_pages_screenshots/preview_or_update.png "Publish box identification")
