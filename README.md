# AJAPH

## Overview

This class makes use of Ajax easier. It allows you to make *asynchronous* (default) or *synchronous* request.

## How to use this

Please see the small example I did in the example folder.
You can also do your testing in here.

## Example

* HTML Code:

        <h1>The Member(s):</h1>
        <div id="data"></div>

* JS Code:

        // Create object
        var oAjax = new AJAPH;
        
        // GET method
        oAjax.send("GET", "member_search.pl", "sex=m&active=1&age=18").setResponseHtml("data");
        
        // POST method
        oAjax.send("POST", "member_data.pl", "user_id=2939&visible=y").setResponseHtml("data");

_Attention, you need JavaScript after the HTML id that must receive the data otherwise it will not work because JavaScript will not find the html ID._

## Author

Pierre-Henry Soria

## License

[General Public License](http://www.gnu.org/copyleft/gpl.html) (GPL) 3 or later.
