# Settings

If you are familiar with MyLife Version 3, settings were managed in the `Standard Pages` folder within Ektron CMS.  That folder contained Smart Forms, which allowed you to set values for text, button labels etc.

Settings are now a top-level item within your site content tree. Click the arrow to the left of the Settings link to display sections of grouped settings.

![title](./settings/settings-all.jpg)

## General Settings

This section includes settings for site-wide content, the footer area and cookie consent banner.

### Content
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Homepage Url|The landing page for your MyLife site|Link Picker|
|Main Menu|The Menu that you want to use for site main navigation (top of screen)|Link Picker|
|Account Menu|A menu of items that you want to show to signed-in users via the drop-down button or side navigation|Link Picker|
|Mobile menu style|Dark or light side navigation on mobile devices|Select|
|Enable key tips|Enable keyboard shortcuts for main menu (users click `Alt` to display)|Checkbox|
|Use glyph icon in menu|Enables icons in the main navigation menu and side menu (on mobiles)|Checkbox|
|Default metadata keywords|The standard SEO keywords that Search Engines will see for any page in your site that does not have it's own specific keywords set|Text|
|Default metadata description|The standard SEO description that Search Engines will see for any page in your site that does not have it's own specific description set|Text|
|Site help title|Title for the Site Help page|Text|

!!! note
    The following settings are deprecated: _Extend header to full width_, _Extend content to full width_ and _Extend footer to full width_.  You can manage row width with the Page Layout tools.

### Footer

The footer area has a standardised layout in two halves.  The left half is free content, which you can change with the Rich text editor.  The right half can have up to three columns of links, curated as menus.  You can populate some or all of these menus.

|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Left column|Left column of links in the footer|Menu builder|
|Middle column|Middle column of links in the footer|Menu builder|
|Right column|Right column of links in the footer|Menu builder|
|Content|HTML content for the left half of the footer, for e.g. logos, address, social media icons, etc.|Rich text|

### Cookie Consent
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Message text|The message that appears to new visitors in the cookie consent banner at the top of the screen|Text|
|Link|An optional link to a page with more information on the cookies that your site uses: We have standard content that covers this|Link picker|
|Link label|Label text for the button to find out more about cookies on your site (button not displayed if empty)|Text|
|Enable cookie consent|Turn on the cookie banner for new visitors. _Note: this is an EU legislative requirement_|Checkbox|

## Account Settings

This section groups all of the individual settings around the secure account page, registering and signing in and out.

### My Account Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro text|Paragraphs of introductory text for visitors at the top of their account page|Rich text|
|My documents headline|Title for the `Documents` page|Text|
|No documents text|Text to display when the user has no documents|Text|
|Upload new documents button label|Label for the document upload button, if you have this setting turned on in Studio|Text|
|My Account options headline|Headline text to display.|
|Help|Any help information that you want to appear in the side help panel if users click it.  This can contain images, links, etc.|Rich text|

### Sign In Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Title|_Not used_| |
|Intro text|Paragraphs of introductory text for visitors at the top of the Login screen|Rich text|
|Login button title|Button label for the `Login` button|Text|
|Register button title|Button label for the `Register` button|Text|
|Forgotten password link title|Title attribute (used by screen readers) for the `Forgotten Password` hyperlink|Text|
|Help|Any help information that you want to appear in the side help panel if users click it.  This can contain images, links, etc.|Rich text|

### Sign Out Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Title|_Not used_| |
|Intro Text|Explanatory information on the `Log out` page|Rich text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

### User Registration Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Title|_Not used_| |
|Intro Text|Introductory paragraph on the `User Registration` page|Rich text|
|Personal details headline|Text for the `Personal details` navigation tab in the user registration journey|Text|
|Address details headline|Text for the `Address details` navigation tab in the user registration journey|Text|
|Contact details headline|Text for the `Contact details` navigation tab in the user registration journey|Text|
|Security details headline|Text for the `Security details` navigation tab in the user registration journey|Text|
|Security questions panel|Explanatory notes in the alert panel above the `Security questions` step|Rich text|
|Memorable information panel|Explanatory notes in the alert panel above the `Security questions` step|Rich text|
|Terms and conditions panel|Explanatory notes in the alert panel above the `Security questions` step|Rich text|
|Terms and conditions label|Label above the terms and conditions|Text|
|Terms and conditions|Your legal terms and conditions text|Rich text|
|Submit button title|Text for the `Submit` button label|Text|
|Cancel button title|Text for the `Cancel` button label|Text|
|Registration completed headline|Text for the `Registration completed` step|Text|
|Registration completed text|Any notes or guidance that you want to appear when the user has completed the registration journey|Rich text|
|Help|Any help information that you want to appear in the side help panel if users click it.  This can contain images, links, etc.|Rich text|

### Activate Account Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Title|_Not used_| |
|Intro Text|Explanatory information on the `Activate Account` page; this page informs users about the process by which they will be sent an email with an activation code and a link they can click to complete the activation|Rich text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

### Update User Details Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Title|_Not used_| |
|Intro Text|Introductory paragraph on the `Change Details` page|Rich text|
|Personal details tab title|Title for the `Personal details` tab|Text|
|Address details tab title|Title for the `Address details` tab|Text|
|Submit button title|Label for the `Submit` button|Text|
|Cancel button title|Label for the `Cancel` button|Text|
|Help|Any help information that you want to appear in the side help panel if users click it.  This can contain images, links, etc.|Rich text|

### Change Password Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Title|_Not used_| |
|Intro Text|Explanatory information on the `Change Password` page|Rich text|
|Submit Button text|Text label for the `Submit` button|Text|
|Submit Button Google analytics event|Google Analytics event name for the `Submit` event|Text|
|Submit Button Google analytics label|Google Analytics event label for the `Submit` event|Text|
|Cancel Button text|Text label for the `Cancel` button|Text|
|Cancel Button Google analytics event|Google Analytics event name for the `Cancel` event|Text|
|Cancel Button Google analytics label|Google Analytics event label for the `Cancel` event|Text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

### Password Recovery Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information on the `Password Recovery` page|Rich text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

## Content Settings

This section groups settings for standard pages, such as `Feedback`, `Site Help` and the `A to Z`.

### Help Requests (FAQs) Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Title|Page title|Text|
|Intro Text|Explanatory information on the `FAQs` page|Rich text|
|Question title|Headline above the input where users type their question|Text|
|Question label|Optional label to the left of the question input box|Text|
|Email label|Optional label to the left of the email input box|Text |
|Email description|Optional help text beneath the email input box|Text|
|Feedback text|Message that gets displayed when a user has submitted their question|Text|
|FAQs|Unbound collection of questions and answers, which will be presented as accordions on screen.  Each FAQ has the fields below:|Collection|
|> FAQ Title|Question text|Text|
|> FAQ Text|Answer text; this can include HTML, images, links and multiple paragraphs for information|Rich text|

### Site Feedback Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Title|Page title|Text|
|Intro Text|Explanatory information on the `Site Feedback` page; this is a static page that allows visitors to send you feedback and ratings|Rich text|
|Rating Title|Text for the rating section headline|Text|
|Comment Title|Text for the comment section headline|Text|
|Email Address Label|Label for the email input box|Text|
|Response Headline|Headline text for the response section, which is displayed after a user has submitted feedback|Text|
|Response Intro Text|Information that you want to add to the response, after a user has submitted feedback|Rich text|
|Analytics label|Google analytics event label for the event triggered when a user submits feedback|Text|
|Analytics Event|Google analytics event name for the event triggered when a user submits feedback|Text|
|Help|Any help information that you want to appear in the side help panel if users click it|Rich text|

### AtoZ Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Title|Page title|Text|
|Intro Text|Explanatory information on the `A to Z` page, which is automatically generated from your site content|Rich text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

### Site Feedback Provider Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Title|Page title|Text|
|Intro Text|Explanatory information on a `Provider Feedback` page; this is a static page that allows visitors to send feedback and ratings for a specific provider|Rich text|
|Rating Title|Text for the rating section headline|Text|
|Comment Title|Text for the comment section headline|Text|
|Email Address Label|Label for the email input box|Text|
|Response Headline|Headline text for the response section, which is displayed after a user has submitted feedback|Text|
|Response Intro Text|Information that you want to add to the response, after a user has submitted feedback|Rich text|
|Analytics label|Google analytics event label for the event triggered when a user submits feedback|Text|
|Analytics Event|Google analytics event name for the event triggered when a user submits feedback|Text|
|Help|Any help information that you want to appear in the side help panel if users click it|Rich text|

## Search Settings

This section contains all of the settings for search results, _MyPad_ and service providers.

### Search Results Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information on the `Search` page|Rich text|
|Result Text|The formatted summary information, which appears above the list of results; this accepts variables (see below this table)|Rich text|
|No Results Text|Information to display when there are no matches found|Rich text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

Result and no-result text above can use placeholders as follows:

    Searchterm: @SearchTerm@ (format of search term is: for 'keyword' near 'location') 
    Number of results: @NumberOfResults@ 
    Display from: @DisplayFrom@ 
    Display to: @DisplayTo@ 
    (e.g Your search '@SearchTerm@' returned @NumberOfResults@ records)

### Search Facets Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Postcodes label|Explanatory information on the `Postcodes` search facet, which allows users to filter results by postcode area|Text|
|Data Source label|Explanatory information on the `Data Source` search facet, which allows users to filter results by source collection, e.g. 'MyLife' (Content) or 'CQC', etc.|Text|
|Formats label|Explanatory information on the `Formats` search facet, which allows users to filter results by file type|Text|
|Keywords label|Explanatory information on the `Keywords` search facet, which allows users to filter results by keywords|Text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

### Featured Providers Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information in a `Featured Providers` section, which appears as a first set of results, akin to Google sponsored results|Rich text|
|View All Records Button text|Label for the `View All Records` button|Text|
|View All Records Button Google analytics event|Google Analytics event name for the `View All Records` event|Text|
|View All Records Button Google analytics label|Google Analytics event label for the `View All Records` event|Text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

### MyPad (View) Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information on the `MyPad` page|Rich text|
|Intro Text for logged-in users|Any additional information that you want to display to signed-in users on the `MyPad` page|Rich text|
|Empty MyPad Text|Text to display when there are no shortlisted items on the page|Text|
|View and Print Button text|Label for the `View and Print` button|Text|
|View and Print Button Google analytics event|Google Analytics event name for the `View and Print` click event|Text|
|View and Print Button Google analytics label|Google Analytics event label for the `View and Print` click event|Text|
|Save to My Account Button text|Label for the `Save to My Account` button|Text|
|Save to My Account Button Google analytics event|Google Analytics event name for the `Save to My Account` click event|Text|
|Save to My Account Button Google analytics label|Google Analytics event label for the `Save to My Account` click event|Text|
|Remove All Button text|Label for the `Remove All` button|Text|
|Remove All Button Google analytics event|Google Analytics event name for the `Remove All` click event|Text|
|Remove All Button Google analytics label|Google Analytics event label for the `Remove All` click event|Text|
|Remove All Confirmation Title|Headline to display in the confirmation dialog when a user removes all shortlisted items|Text|
|Remove All Confirmation Text|Information to display in the confirmation dialog when a user removes all shortlisted items|Rich text|
|Remove All Confirmation Button label|Label for the `Confirm` button|Text|
|Cancel Button label|Label for the `Cancel` button|Text|
|View MyPad Button text|Label for the `View MyPad` button|Text|
|View MyPad Button Google analytics event|Google Analytics event name for the `View MyPad` click event|Text|
|View MyPad Button Google analytics label|Google Analytics event label for the `View MyPad` click event|Text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

### MyPad (Edit) Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Add Intro Text|Explanatory information on the `MyPad` page `Add` section|Rich text|
|Edit Intro Text|Explanatory information on the `MyPad` page `Edit` section|Rich text|
|Help Information Title|Headline text for the help section|Text|
|Help Information Text|Detailed help section information|Rich text|
|Add to MyPad Accordion Button text|Label for the `Add to MyPad Accordion` button|Text|
|Add to MyPad Accordion Button Google analytics event|Google Analytics event name for the `Add to MyPad Accordion` click event|Text|
|Add to MyPad Accordion Button Google analytics label|Google Analytics event label for the `Add to MyPad Accordion` click event|Text|
|Add to MyPad Button text|Label for the `Add to MyPad` button|Text|
|Add to MyPad Button Google analytics event|Google Analytics event name for the `Add to MyPad` click event|Text|
|Add to MyPad Button Google analytics label|Google Analytics event label for the `Add to MyPad` click event|Text|
|Remove from MyPad Button text|Label for the `Remove from MyPad` button|Text|
|Remove from MyPad Button Google analytics event|Google Analytics event name for the `Remove from MyPad` click event|Text|
|Remove from MyPad Button Google analytics label|Google Analytics event label for the `Remove from MyPad` click event|Text|
|Edit Notes Button text|Label for the `Edit Notes` button|Text|
|Edit Notes Button Google analytics event|Google Analytics event name for the `Edit Notes` click event|Text|
|Edit Notes Button Google analytics label|Google Analytics event label for the `Edit Notes` click event|Text|
|Save Button Button text|Label for the `Save Button` button|Text|
|Save Button Button Google analytics event|Google Analytics event name for the `Save Button` click event|Text|
|Save Button Button Google analytics label|Google Analytics event label for the `Save Button` click event|Text|
|Cancel Button Button text|Label for the `Cancel Button` button|Text|
|Cancel Button Button Google analytics event|Google Analytics event name for the `Cancel Button` click event|Text|
|Cancel Button Button Google analytics label|Google Analytics event label for the `Cancel Button` click event|Text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

### Provider Details Settings

|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Service summary|Title for the Service Summary section on Provider Details page.|Text|
|Service details|Title for the Service Details section on Provider Details page.|Text|
|Documents tab|Title for the Documents tab, where you allow Providers to upload and display documents.|Text|
|Ratings and reviews|Title for the Ratings tab, where this feature is turned on.|Text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

### Provider Registration Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information on the `Provider Registration` page|Rich text|
|Organisation details headline|Text for the `Organisation Details` section heading|Text|
|Address details headline|Text for the `Address Details` section heading|Text|
|Organisation contact details headline|Text for the `Organisation Contact Details` section heading|Text|
|Contact details headline|Text for the `Contact Details` section heading|Text|
|Service details headline|Text for the `Service Details` section heading|Text|
|Terms and conditions label|Label for the terms and conditions section|Text|
|Terms and conditions|Text for your legal terms and conditions for use of the site|Rich text|
|Submit button label|Label for the `Submit` button|Text|
|Cancel button label|Label for the `Cancel` button|Text|
|Registration completed headline|Text for the `Registration completed` heading, which is displayed after successful registration|Text|
|Registration completed text|Additional information that you want to display to a provider after they have registered|Rich text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

## Guides Settings

This section covers settings for `Guides`, including the overview page (a list of all available Guides) and settings for each Guide as a user steps through the journey.

### Guides Overview Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information on the `Guides Overview` page|Rich text|
|Row Height (px)|Minimum height for each row of cards.  Expects a number.  A card is a clickable link with a title and optionally some text and a picture|Text|
|Items|A collection of guide items that will be displayed as clickable cards.  Each card links to a `Guide`|Collection|
|> Item: Title|The Guide name - appears as the card headline|Text|
|> Item: Teaser|Short body text to explain what the `Guide` is about|Text|
|> Item: Image|A picture to display on the card.  Ideally square, or all the same aspect ratio and dimensions|Image Picker|
|> Item: Link|Link to the related `Guide`; this can be typed as a url, or you can select the `Guide` content item|Link picker|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

### Guides Settings
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information at the start of each `Guide`|Text|
|Save guide to my account text|Information about saving the `Guide` generated by the user's answers|Text|
|Save to my account button label|Label text for the `Save to my account` button|Text|
|View and print guide text|Information about reading or printing the `Guide` generated by the user's answers|Text|
|View and print button label|Label text for the `View and print` button|Text|
|Save guide to my computer text|Information about saving the `Guide` to the user's computer|Text|
|Save to computer button label|Label text for the `Save to my computer` button|Text|
|Send guide to an email address text|Information about sending the `Guide` as a PDF attachment in an email to nominated recipients|Text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|