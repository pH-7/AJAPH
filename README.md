# AJAPH

## Overview

This class makes use of Ajax easier.

## How to use this

Please see the small example I did in the example folder.
You can also do your testing in here.

## Example:

* HTML Code:

        <p>The User:</p>
        <div id="data"></div>

* JS Code:

        var oAjax = new AJAPH;
        oAjax.send("GET", "member_data.pl", "user_id=2939&visible=y").response('text', "data");

_Attention, you need JavaScript after the HTML id that must receive the data otherwise it will not work because JavaScript will not find the html ID._

## Author

Pierre-Henry Soria

## License

[General Public License](http://www.gnu.org/copyleft/gpl.html) (GPL) 3 or later.

