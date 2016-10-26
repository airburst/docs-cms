# Content Articles

This section covers creating content articles or blocks, which can be presented as full pages, or within widgets in a more complex page layout.

`HTML Content` items are the simplest way to build a page of information.  You can paste text, tables and pictures from Microsoft Word directly into the editor and preview it very quickly.

They are particularly good for textual and tabular content, as well as blocks that you might want to reuse in more complex page layouts.

Once you have created a draft item that you are happy with, it is essential to add good [metadata](#metadata) in order for search engines like Google to index and help the public find your pages.

## Create an HTML Content Article

You can create `HTML Content` items inside any folder.

* Hover on the folder (in the site tree) that you want to create the article in
* Click on the ellipsis icon that appears to the right of the folder name
* Select `HTML Content` from the `Create` panel that appears

![content](./content-articles/create-content.jpg)

* The details panel will appear, set to the `Content` tab, ready for you to start typing
* The quickest way to start off is to paste in existing information, typically from other websites or Microsoft Word documents

![content](./content-articles/paste-from-word.jpg)

* Paste works well in Umbraco, generating very clean markup

![content](./content-articles/source-code.jpg)


You can of course take finer control of the content.  The editor menu bar supports the following actions:

![content](./content-articles/menu.jpg)

|Item|Description|
| ------------- | ------------- |
|`<>`|This is the `HTML Source` menu.  Click this button to show and edit the HTML markup for your page.|
|`Formats`|Heading styles from H1 to H6.  Clicking ths button will apply the heading style to any selected text in the editor.|
|`B`|Make selected text bold.  You can do the same by pressing the keyboard shortcut `Ctrl + B`.|
|`I`|Make selected text italics.  You can do the same by pressing the keyboard shortcut `Ctrl + I`.|
|`Left`|Left-justify text.|
|`Centre`|Centre text.|
|`Right`|Right-justify text.|
|`Bullets`|Start an unordered (bullet) list, or apply bullets to the selected text.|
|`Numbers`|Start an ordered (numeric) list, or apply numbering to the selected text.|
|`Outdent`|Outdent text (or picture, etc.).|
|`Indent`|Indent text.|
|`Link`|Add a link to the document.  This invokes the [links picker](#links-picker) to select a content item, image or external url|
|`Image`|Add a picture to the document.  This invokes the [media picker](#media-picker) to select or upload an image.|
|`Macro`|Not used|
|`Embed`|Not used|

## Links Picker

The links picker is a handy panel to search for and select another content item, image or external url and insert it as a link into your current item.

The dialog allows you to type in a full Url, set the link text in the `Page Title` box and choose whether the target is in the current window or a new one (recommended for external links).

!!! note
    The Search box at the bottom filters your content results by name as you type.  This is a very quick way to find the link that you want.

![content](./content-articles/links-picker.jpg)

Once you are done, click `Select` to return to the editor.

The `Link to file` button at the bottom of the panel switches you to the [media picker](#media-picker) to link to a file or other asset instead of a content item.

## Media Picker

The media picker lets you search for an existing image or document - or upload a new one - and insert it as a link into your current content.

![content](./content-articles/media-picker.jpg)

As above, the search box at the top does a great job of quickly filtering results as you type.

![content](./content-articles/search-media.jpg)

## Metadata

Metadata is essential for Search Engine Optimisation (SEO).  The public will find your pages by using search engines like Google or Bing. Metadata is one of the key ways that you tell those search engines what each page is about and how to index it.

Good SEO practises will drive more views to your site, because your results will show up with a higher rank and a clear synopsis.

You can find the `Metadata` tab in the details panel for most types of content.  The tab lets you configure the following things:

|Item|Purpose|
| ------------- | ------------- |
|Keywords|A set of comma separated words that you guess or expect the public to use when searching for this kind of page.  Try not to stuff with a huge list of words; that counts against you!|
|Description|A summary of the page, typically around 70 - 100 words. Google will display this synopsis below the link in their results.|
|Show in search|Choose whether or not to include this page in MyLife search results.  Checked by default.|
|Include in A to Z|Choose whether or not to include this page in the automatically-curated MyLife A to Z page.  Unchecked by default.|
|Alias|A short url that appears in the public link to this page.  Note that Umbraco uses the folder path and page title as the default alias, so if you are using short, pithy naming conventions for your folders and articles, then you will already have a good alias.|
|Tags|You can tag content pages with the same categories/tags system used by service providers in Studio.  Tags are arbitrary text that you can use to group pages together.  They will appear in search results as facets, so users can click on related items.  The tags control is self-explanatory; select a category (populated from your list in Studio) and start typing tag name(s).  It uses autocomplete to match existing tags, or you can set new ones.|

## Help

If you set `Help` on a content item, then a help tab appears on the page in MyLife.  Users can click the tab to reveal the help information.

The `Help` tab combines two previously separate methods for defining help information on a page. It contains an Editor, in which you can create rich information in exactly the same way as you did for the main content.

Help can contain its own images, links and styled content.

## Other actions

To remove, move, copy or rollback an `HTML Content` item, see the [Managing Content](../file-management) section.
