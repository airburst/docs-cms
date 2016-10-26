# Guides

A `Guide` is a short, interactive set of questions or statements that a user picks to find out more information.

The `Guide` uses their responses to curate content and search results into a single document, which they can view online, save to their computer as a PDF file, save to their Mylife secure account, or send by email.

You can find examples on most Local Authority Mylife sites, for example:

* [LB Redbridge](https://mylife.redbridge.gov.uk/guides/guides.aspx)
* [Glasgow City Council](https://www.yoursupportglasgow.org/guides/guides.aspx)
* [Telford](https://telford.mylifeportal.co.uk/guides/guides.aspx)

This section explains how to create a Guide.

!!! note
    Prior to MyLife version 2, Guides were generated as pure HTML, rather than being living, easily-editable content types.  There remain a number of 'legacy' Guides in customer sites.  We do not provide tools to manage legacy Guides: they will still work, but any new Guides should be created with this content widget.

## Create a Guide

* As with all new content, start by hovering over the folder in the site content tree, that you want to create the Guide inside
* Click on the ellipsis icon that appears to the right of the folder name
* Select `Guide` from the `Create` panel options. 

![Create guide](./guides/create-guide.jpg)

!!! note
    If 'Guide' does not appear as an option then it has not been enabled as a valid content type in this folder, or a parent of this folder

* You will now see a details panel on the right, opened at the `Guide` tab

![Guide options](./guides/guide-options.jpg)

* You can configure the entire Guide in this screen; each field is explained below:

|Item|Description|
| ------------- | ------------- |
|Title|The headline text displayed on the first step of the `Guide`|
|Intro text|Introductory or explanatory text (and pictures) that appears at the top of the first step of the `Guide`|
|Completion text|Explanatory notes, which appear after the user has completed the `Guide`|
|Container doc|A content link-picker to link a container document. The container document is generally created once as a site-wide structure for presenting the final information to a user. See below for notes on building a container doc.|
|Questions|A collection of one or more question or statement groups, e.g. _"What can I do to become healthier?"_. Each question has multiple fields, described in the next table.|

Question Fields

|Question Item|Description|
| ------------- | ------------- |
|Title|The question title, e.g. _"What can I do to become healthier?"_|
|Text|Optional notes to follow the question.|
|Subtitle|Directions for completing the questions or statements, e.g. _Please tick all statements that apply to you_|
|Options|A collection of options; the answers that a user can check.  See the table below for details on options fields.|

Option Fields

|Option Item|Description|
| ------------- | ------------- |
|Statement|The statement that will appear next to a checkbox, e.g. _I want to improve my diet_.|
|Information|The detailed information that will be added into the final PDF for any user who checks this statement.|

### Notes on fulfilling Option Information

Option information is the key part of each Guide question; it will be compiled into the user's tailored response document. The `Rich Editor` input box allows you to create complete content articles, with pictures, links.  You can find more information on creating content items in the [Content Articles](../content-articles) section.

This Editor also lets you embed the results from specific `Featured Provider Lists` that you have set up in Studio. You will need to find the id number for the correct list and can then add the text `{#ProviderList=x#}`, where x = the id.

## Other Actions

You can remove, move, copy and rollback `Guides` just like any other content item. Please refer to the [Content Management](../file-management) section for more information.
