#  JQuery Plugin For Collapsible Fieldset

* Copyright: © 2010 Lucky <bogeyman2007@gmail.com>
* License: [GPL](http://www.gnu.org/licenses/gpl.html)
* Homepage: [w3shaman](http://w3shaman.com/article/jquery-plugin-collapsible-fieldset)

If you need to create collapsible and expandable fieldset, this jQuery plugin
might be helpful. This plugin can collapse or hide fieldset and its content
by clicking its `legend`. You can also decide the initial state for your
fieldset wheter it's expanded or collapsed. The separated CSS file will also be
useful if you need to modify the fieldset appearance. By the way, this
plugin is named **coolfieldset**.

## Using Coolfieldset

Just like others jQuery plugin, this plugin is also easy to use. Just
include jQuery and this plugins inside the &lt;head> tag.

    <script language="javascript" type="text/javascript" src="js/jquery.js"></script>
    <script language="javascript" type="text/javascript" src="js/jquery.coolfieldset.js"></script>

And include the CSS file for styling the fieldset.
    
    <link rel="stylesheet" type="text/css" href="css/jquery.coolfieldset.css" />

Prepare your fieldset.
    
    <fieldset id="fieldset1" class="coolfieldset">
      <legend>Legend</legend>
      <div>
        <p>Fieldset content goes here.</p>
      </div>
    </fieldset>

And finally, use this script to turn your fieldsets into collapsible.
    
    <script language="javascript" type="text/javascript">
      $('#fieldset1').coolfieldset();
    </script>

## Example

The more complete example be seen [here](http://stuff.w3shaman.com/jquery- plugins/coolfieldset/).

