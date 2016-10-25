# Settings

If you are familiar with MyLife Version 3, settings were managed in the `Standard Pages` folder within Ektron CMS.  That folder contained Smart Forms, which allowed you to set values for text, button labels etc.

Settings are now a top-level item within your site content tree. Click the arrow to the left of the Settings link to display sections of grouped settings.

![title](./images/image.jpg)

## General Settings

This section includes site settings, the footer area and cookie consent banner.

### Site
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Homepage Url|The landing page for your MyLife site|Link Picker|
|Main Menu|The Menu that you want to use for site main navigation (top of screen)|Link Picker|
|Account Menu|A menu of items that you want to show to signed-in users via the drop-down button or side navigation|Link Picker|
|Account Options Menu|A menu of items that you want to show to |Link Picker|
|Enable cookie consent|Turn on the cookie banner for new visitors. _Note: this is an EU legislative requirement_|Checkbox|
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
|Intro text|The message that appears to new visitors in the cookie consent banner at the top of the screen|Text|
|Link|An optional link to a page with more information on the cookies that your site uses: We have standard content that covers this|Link picker|
|Link label|Label text for the button to find out more about cookies on your site (button not displayed if empty)|Text|

## Account Settings

This section groups all of the individual settings around the secure account page, registering and signing in and out.

### Login
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro text|Paragraphs of introductory text for visitors at the top of the Login screen|Rich text|
|Login button title|Button label for the `Login` button|Text|
|Register button title|Button label for the `Register` button|Text|
|Forgotten password link title|Title attribute (used by screen readers) for the `Forgotten Password` hyperlink|Text|
|Help|Any help information that you want to appear in the side help panel if users click it.  This can contain images, links, etc.|Rich text|

### My Account
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro text|Paragraphs of introductory text for visitors at the top of their account page|Rich text|
|My documents headline|Title for the `Documents` page|Text|
|No documents text|Text to display when the user has no documents|Text|
|Upload new documents button label|Label for the document upload button, if you have this setting turned on in Studio|Text|
|Action title|Title for the `Tasks` page|Text|
|Action description|Descriptive paragraphs for the `Tasks` page|Rich text|
|Message title|Title for the `Messages` page|Text|
|Message description|Descriptive paragraphs for the `Messages` page|Rich text|
|Document title|Title for the `Documents` page|Text|
|Document description|Descriptive paragraphs for the `Documents` page|Rich text|
|Help|Any help information that you want to appear in the side help panel if users click it.  This can contain images, links, etc.|Rich text|

!!! warning
    __TODO__
    Check 'Message' in table above. And 'Action'

### Update User Details
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Introductory paragraph on the `Change Details` page|Rich text|
|Personal details tab title|Title for the `Personal details` tab|Text|
|Address details tab title|Title for the `Address details` tab|Text|
|Submit button title|Label for the `Submit` button|Text|
|Cancel button title|Label for the `Cancel` button|Text|
|Help|Any help information that you want to appear in the side help panel if users click it.  This can contain images, links, etc.|Rich text|

### User Registration
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
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

### Activate Account
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information on the `Activate Account` page; this page informs users about the process by which they will be sent an email with an activation code and a link they can click to complete the activation|Rich text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

### Change Password
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information on the `Change Password` page|Rich text|
|Submit Button text|Text label for the `Submit` button|Text|
|Submit Button Google analytics event|Google Analytics event name for the `Submit` event|Text|
|Submit Button Google analytics label|Google Analytics event label for the `Submit` event|Text|
|Cancel Button text|Text label for the `Cancel` button|Text|
|Cancel Button Google analytics event|Google Analytics event name for the `Cancel` event|Text|
|Cancel Button Google analytics label|Google Analytics event label for the `Cancel` event|Text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|


### Log Out
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information on the `Log out` page|Rich text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

### Password Recovery
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information on the `Password Recovery` page|Rich text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

## Content Settings

xx

### Help Requests (FAQs)
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information on the `FAQs` page|Rich text|
|Question title|Headline above the input where users type their question|Text|
|Question label|Optional label to the left of the question input box|Text|
|Email label|Optional label to the left of the email input box|Text |
|Email description|Optional help text beneath the email input box|Text|
|Feedback text|Message that gets displayed when a user has submitted their question|Text|
|FAQs|Unbound collection of questions and answers, which will be presented as accordions on screen.  Each FAQ has the fields below:|Collection|
|> FAQ Title|Question text|Text|
|> FAQ Text|Answer text; this can include HTML, images, links and multiple paragraphs for information|Rich text|


### Site Feedback
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information on the `Site Feedback` page; this is a static page that allows visitors to send you feedback and ratings|Rich text|
|Rating Title|Text for the rating section headline|Text|
|Comment Title|Text for the comment section headline|Text|
|Email Address Label|Label for the email input box|Text|
|Response Headline|Headline text for the response section, which is displayed after a user has submitted feedback|Text|
|Response Intro Text|Information that you want to add to the response, after a user has submitted feedback|Rich text|
|Analytics label|Google analytics event label for the event triggered when a user submits feedback|Text|
|Analytics Event|Google analytics event name for the event triggered when a user submits feedback|Text|
|Help|Any help information that you want to appear in the side help panel if users click it|Rich text|

### AtoZ
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
|Intro Text|Explanatory information on the `A to Z` page, which is automatically generated from your site content|Rich text|
|Help|Any help information that you want to appear in the side help panel if users click it.|Rich text|

### Site Feedback Provider
|Setting|Description|Type|
| ------------- | ------------- | ------------- |
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

xx

## Guides Settings

xx