# Managing Content

This section covers basic tasks such as organising your site folder structure, setting breadcrumbs, and performing `Actions` such as creating, moving, copying and removing content items.

## Navigating folders

Open Umbraco CMS and click on the Content button in the left (dark) panel.  You will initially see one folder with the name of your site.  Hover over this folder to reveal an arrow to the left and an ellipsis to the right.  Click the arrow to reveal the folder tree.

If you have migrated from MyLife version 3 then the folder structure should be exactly the same, with the addition of two folders at the top for [Menus](../menus) and [Settings](../settings).

![List of folders](/file-management/folders.jpg)

You can drill down into the folder tree with the same method; click the arrow to the left of the folder name.

!!! Note
    You can use the search box above the folder tree to quickly find deeply nested folders by name

## Content Properties

If you click on a folder  then the selected item will have a blue background and a details panel will appear to the right.  

The specific tabs in the details panel will vary depending on the type of content that you are working on.  E.g. the details for a folder has a `Breadcrumbs` tab and a `Properties` tab, while an article has `Content`, `Metadata`, `Help` and `Properties`.  

> You will rarely use `Properties`, but the other tabs are more useful and are explained in these docs.

!!! Note
    If you are using a screen narrower than 1000px wide, then the tree will disappear and you will only see the details panel.  Click on the `Content` button in the left bar to go back.

## Breadcrumbs

Breadcrumbs can help users to navigate when you have deeply nested content, such as drill-down menus or rich sections within your site.  They appear as a sequence of links beneath the header.

![Breadcrumb example](/file-management/breadcrumb-in-page.jpg)

__Breadcrumbs are only set at the folder level.__

To set a breadcrumb, click on a folder and navigate to the `Breadcrumb` tab in the details panel.

![Breadcrumbs](/file-management/breadcrumb.jpg)

There are two strategies for setting breadcrumbs:

1. Set a top level breadcrumb to _Home_ and then use inherittance.  This means that you only need to set one breadcrumb at each level.  This is easier to manage __but__ it does tie your breadcrumb structure to your folder structure.
2. Set a full trail as a collection of breadcrumbs on the folder.  This provides a more portable and flexible structure (the full trail moves with the folder), __but__ requires more work on each folder.

You can use a combination of the above, e.g. start with a trail at an arbitrary level in your folder tree and then turn on inherittance in child folders.

### How to set a Breadcrumb

* Click on the folder that you want to start the breadcrumb trail from
* Click the `Breadcrumb` tab in the details panel
* If you want to inherit the existing trail from the parent folder, then check the `Inherit trail from parent folders` checkbox
* __For each breadcrumb that you want to add to the trail__:
* Expand the Breadcrumb item to show inputs for Label and links
![Add Breadcrumb](/file-management/add-breadcrumb.jpg)
* Type in a short name for the crumb and use the link picker to navigate to an existing folder; when a user clicks the crumb, this is the folder they will redirect to
![Select Breadcrumb Folder](/file-management/select-breadcrumb-folder.jpg)
* Click `Submit` to Save

![Breadcrumb actions](/file-management/breadcrumb-actions.jpg)

* You can use the `+` button to add more breadcrumbs: The whole sequence will be displayed as separate links in the trail.
* The `sort` button allows you to reorder crumbs with click and drag
* The `reset` button does ...
* The `x` button deletes the crumb

## Rename Content

* To rename a content item - whether a folder, article or anything else - click on the item in the site folder tree.  
* Above the details panel you will see a text input box with the name of the item.
* Change the text and click `Save and publish`.

![Rename content](/file-management/rename-folder.jpg)

## Create Content

* To create a new folder or content item, hover over the folder in the site tree that you want to create the new item within
* While hovering you will see an ellipsis to the right of the folder name
* Click the ellipsis icon to show the `Create` panel

![Create folder](/file-management/folder-create.jpg)

* Click on the type of item that you want to create
* You will see an empty details panel for the new content item type
* Fill in details for the new item and preview, save or publish

## Delete content

* To delete a content item, click on the item in the site tree that you want to remove
* You will see an `Actions` button to the top right of the screen
* Click the `Actions` button to show a list of actions

![Actions list](/file-management/actions.jpg)

* Click `Delete` item in the actions list
* Click `OK` in the confirm panel

![Actions list](/file-management/confirm-delete.jpg)

## Move or Copy Content

### When to move content

You may find yourself wanting to move content into new folders or sub-folders for better site organisation, or because the inheritted breadcrumbs from a folder are inappropriate.

Equally, you may have a great page that you wish to use as a template for creating a new one, and stating from a copy gives you a head start and better consistency.

Move and Copy are easy to use and available on all content items and folders.  You can only move or copy content into a destination folder (i.e. not into another article).  If you are nesting folders then ensure that the destination has been created before you try to move.

### How to move content

* Open the Content View.
* Within your site folder structure, click on the content item that you want to move or copy.
* Select `Move` (or `Copy`) from the actions list at the top right of the page.
* Select the destination folder that you want to move or copy content to.  This is the tree in the middle panel below.
* Click the `Move` button (bottom of middle panel).

![Move or copy](/file-management/move.jpg)

* You will see an `Ok` message when the move or copy is complete.

![Complete the move](/file-management/do-move.jpg)

!!! Note
    After copying a content item or page, you should give the new copy a distinct alias and title

## Sort Content

By default, content and folders appear (within a folder) in the order that you create them, rather than e.g. alphabetical or any other sorting.  You can change the order of items in a folder using the `Sort` action.

* Click on the folder in which you want to sort content items
* Select `Sort` from the actions list at the top right of the page

![Sort action](/file-management/sort-1.jpg)

* The middle panel shows the list of items __in the current folder__ and a sequence number

![Sort action](/file-management/sort-2.jpg)

* Click and drag items into the position that you want
* Click `Save` to keep the change, or `Cancel` to go back

![Sort action](/file-management/sort-3.jpg)

## Rollback Content

If you make a mistake, or simply want to revert to an earlier version of a page then you can use `Rollback` to do so.

* Click on the item that you want to Rollback
* Click `Rollback` in the actions menu at the top right of the screen
* The middle panel of the screen shows rollback options
* Select the version that you want to rollback to

![Rollback](/file-management/rollback.jpg)

* Below the version select you will now see a summary of the differences between the current and selected rollback versions.  You can view this as `Diff` or `HTML`.  Leave it as `Diff` to see highlighted changes.

![Diffs](/file-management/diffs.jpg)

* When you are happy, click the `Rollback` button
* The screen will ask you to `Close the window`
* __Refresh your browser__ to see the rolled-back item __It is not saved yet!__
* Click `Save and publish` (or just save if you want to keep as draft)

## Save and Publish

After making changes to a content item, you can save it as draft or publish it. 

Draft content is not visible to users visiting your site, but can still be previewed, so is a great way to build out new content without needing a separate environment or approval workflows.

The default action for the `Save and publish` button is just that: to publish changes.  However, you can click the options arrow to the right of the button and reveal separate actions to `Save` or `Unpublish` the current item.

![Save and publish button](/file-management/save-publish.jpg)

You can see the status of items in the folder tree via the presence (or not) of a small green dot.  The dot means that the item is in draft and is not published.

![Draft](/file-management/draft.jpg)

## Audit Trail

You can see a full audit trail of changes to an item.

* Click on the item that you want to audit in the site folder tree
* Click `Audit trail` in the actions menu at the top right of the screen
* The screen shows a list of actions, who made the change and when

![Audit](/file-management/audit.jpg)