Requirements
============
 
 *  jQuery
 *  jQuery UI
 *  Bootstrap (optional)

How to include
==============

In your <code>&lt;head&gt;</code>-Tag:

	<link href="css/bootstrap.min.css" rel="stylesheet"> <!-- OPTIONAL -->
	<script src="js/jquery-1.9.1.min.js" type="text/javascript"></script>
	<script src="js/jquery-ui-1.10.1.custom.min.js" type="text/javascript"></script>
		
	<script src="js/jquery.etformvalidation.js" type="text/javascript"></script>

How to use
==========

	<script type="text/javascript">
		$(document).ready(function() {
			$("form").etformvalidation(/* options */);
		});
	</script>

Options
=======

 *  bootstrap
    * true / false (default)
 *  dateFormat
    * mm/dd/yy (default)
 *  error
    * Please fill in the whole form.

License
=======

>Copyright (c) 2013 Fabio Poloni

>Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

>The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

>THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
