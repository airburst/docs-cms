# Page Layouts

`Pages` let you take greater control of your content layout, allowing for multiple rows and sections, into which you drop configurable [content widgets](../widgets).

They are useful for landing pages around a topic, such as Health and Wellbeing, or Dementia Support, where you may have a lot of content that you want to surface in one place.

Version 4 adds more flexibility to the types of layout that you can achieve, allowing for full-width content and individual row and cell styling.

Pages use [responsive design](https://en.wikipedia.org/wiki/Responsive_web_design) to automatically reflow on smaller devices.

## Create a new Page

* As with all new content, start by hovering over the folder in the site content tree, that you want to create the `Page` inside
* Click on the ellipsis icon that appears to the right of the folder name
* Select `Page` from the `Create` panel options. 

![Create Page layout](./page-layout/create-page.jpg)

!!! note
    If you cannot see an option for _Page_ then it has not been added as a content type to this folder, or one of its parents. You can change the content types that a folder can contain.

* You will see a details panel on the right of the screen, open at the `Layout` tab
* Give the new page a meaningful, short name; note that this name will be used as the default alias unless you change it in the [Metadata](../content-articles/#metadata) tab
* Then add a row and save

## Add a Row

* When you initially create a `Page`, or add a new row, the `Layout` tab shows a visual list of row layouts to choose from
* There are even layouts for 1, 2, 3 or 4 columns and ratio layouts for pages where e.g. you want a thin menu with full height in the page (or part of the page)

![Add a row](./page-layout/add-a-row.jpg)

* Click on the layout that you want to use

![Pick a row](./page-layout/pick-a-row.jpg)

* And the row is displayed with cells, ready for you to add content
* In the figure below you can see a `+` button below the row.  This appears beneath every row in your page.  Click this icon to add new rows between existing ones, using the same process described above

![Add a row](./page-layout/row-added.jpg)

## Add Content to a Row

You can add or replace the content in a cell at any time.

* Click on the `Add content` drop zone in a cell

![Add content](./page-layout/add-content.jpg)

* A widgets picker dialog will appear; select the type of content widget that you want to add to this cell

![Pick a widget](./page-layout/pick-widget.jpg)

* You can configure the [row settings](#row-settings) to set the styles that you want

See the [widgets](../widgets) section for more details on the types of content that you can add and how to change their settings

## Change Cell Settings

Each cell has a few settings that you can edit. 

* Click on a cell to make its settings icon appear at the top-right
* Click the settings icon

![Cell settings](./page-layout/change-cell-settings.jpg)

* A cell settings panel appears on the right of the screen
* You can give the cell a class name, which will apply a style from your theme
* And you can set a background image for the cell, using a [media picker](../content-articles/#media-picker)

![Cell settings](./page-layout/cell-settings.jpg)

## Edit a Page

Pages can be changed at any time and like all other content, you can preview, save as a draft or publish them for the public to see.

* Navigate to your page in the site folder tree, or (recommended) use the search box above the content tree to quickly find your page by name
* Click on the page to display the details panel

![Page layout](./page-layout/page-layout.jpg)

* You can click on a row to change its settings or remove it (see below)
* You can click on a cell to change its settings; and
* You can click on a widget inside a cell to change its settings, or remove it entirely
* Remember to click `Save and publish` to store any changes

## Row Settings

Rows now have a number of settings that you can use to control the layout within your pages.

* With the `Layout` panel open, click on the name of any row (or the top of the row, level with the name) to display a blue background with settings and bin icons

![Page layout](./page-layout/row-settings.jpg)

* Click the settings icon to reveal a settings panel on the right of the screen

![Page layout](./page-layout/row-settings-open.jpg)

* And scrolled down to the bottom of the settings panel..

![Page layout](./page-layout/row-settings-open-2.jpg)

* Each setting is described in the table below:

|Setting|Description|
| ------------- | ------------- |
|Class|An optional class name or names, separated by spaces.  If these match with named styles in your site theme, then the style(s) will be applied to the row.  In this way, you can customise specific row styles that you want to reuse.|
|Padding|Select a padding from the list (none, x-small, small, medium, large, x-large) to apply an amount of padding above and below the widget, __but not above and below the row__. The default value is _medium_.  Exact padding amounts are in the table below.|
|Margin|Select a margin from the list (none, x-small, small, medium, large, x-large) to apply an amount of margin above and below the row, __but not inside the row__. The default value is _none_. Exact margin amounts are in the table below.|
|Row layout|Select an option from the list (default, full-width, full-width-stretched).  Row layout options are demonstrated [below](#row-layout-options).|
|Background image|Optionally set a picture to display behind the row.  This is a good way to present text above an image.  If you do this, __we strongly advise that you darken the image and only use white text__.|
|Background colour|Optionally set a colour for the row background.  This is an effective way to break up long pages or emphasise banners.  If you set a background colour, we recommend that you use a full width layout. You can type in a Hex colour if you know it, or use the colour picker to visually find one (see below).|

### Padding and Margin Values

The following values are used when you choose a margin or padding row style. All values are in em units.

|Style|Mobile|Tablet ( > 767px)|Desktop (> 992px)|
|---|---|---|---|
|None|0|0|0|
|x-small|1|1.5|2|
|small|2|3|4|
|medium|3|4.5|6|
|large|4|6|8|
|x-large|5|7.5|10|


### Colour picker

![Page layout](./page-layout/colour-picker.jpg)

## Row Layout Options

Rows can be set in one of three layouts, giving your pages more flexibility.

* __Default:__ This is how all rows are laid out in MyLife version 3. The widget contents of the row are all inside a container and so is the row.  A background colour has been added in the figure below to illustrate.

![Default layout](./page-layout/default.jpg)

* __Full Width:__ The widget contents remain inside a container, but the row now extends to the full width of the screen. This allows for full-width coloured areas such as banners.

![Default layout](./page-layout/fw.jpg)

* __Full Width Stretched:__ The row extends to the full width of the screen and so do its contents. This layout suits images, carousels and videos that you want to reach edge-to-edge on the screen.

![Default layout](./page-layout/fws.jpg)

## Reorder Rows

Having placed rows into a page, it is simple to move them into a different order.

* In the `Layout` tab, click on the `Reorder` link at the top right of the screen

![Reorder rows](./page-layout/reorder.jpg)

* This hides the content of each row and displays them as a stack of horizontal bars, with the name of content widgets in each cell
* Click and drag a row to change its position
* Click `I am done reordering` when the rows are laid out as you want
* Click `Save` or `Save and publish` to store the change

![Done Reordering rows](./page-layout/done-reordering.jpg)

## Other Actions

You can remove, move, copy and rollback `Pages` just like any other content item. Please refer to the [Content Management](../file-management) section for more information.

## Metadata

As with any other page that you publish, it is very important to get the best SEO rank that you can. See more details on using the [Metadata](../content-articles/#metadata) tab.