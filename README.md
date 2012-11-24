CKEditor More plugin
====================

This is modified from the WPMore plugin in the CKEditor extension for WordPress.<br />
Copyright and license for the original source and author are in the docblock for plugin.js.

The WPMore plugin is used to insert the WordPress "more" link. For more information on the
"more" link, see http://en.support.wordpress.com/splitting-content/more-tag/

The most important change is the wrapping of text before and after the More tag.<br />
Sample text: The quick brown fox jumps over the lazy old dog.<br />
More tag inserted just before the word 'over'.<br />
Original effect: ```<p>The quick brown fox jumps</p><!--more--><p>over the lazy old dog.</p>```<br />
Changed effect:  ```The quick brown fox jumps <!--more-->over the lazy old dog.```

### Installation
1. Clone this project and copy the wpmore folder into the plugins directory in your CKEditor installation.
2. A demo page has been placed in wpmore to show how to include the plugin and add the button to the toolbar.