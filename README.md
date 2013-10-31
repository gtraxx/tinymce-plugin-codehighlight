TinyMCE codehighlight
============================

 Insert code with codehighlight for tinyMCE 4 
 
###Installation
 * Download skin
 * Unzip archive
 * Move folder bootstrap in tinyMCE (tiny_mce/plugins/)

###Language
 * English
 * French
 
 You can send me translations in other languages

Authors
-------

 * Gerits Aurelien (Author-Developer) contact[at]aurelien-gerits[point]be

###Configuration
 ```html
<script type="text/javascript">
tinymce.init({
	selector: "textarea",
	plugins: [
			"advlist autolink lists link image charmap print preview anchor",
			"searchreplace visualblocks code fullscreen",
			"insertdatetime media table contextmenu paste codehighlight"
			],
	toolbar: "insertfile undo redo | styleselect | bold italic | alignleft aligncenter alignright alignjustify | bullist numlist outdent indent | link image| codehighlight"
	});
</script>
```

### Old Version

[Plugin CodeHighlight for tinyMCE 3](http://www.magix-dev.be/fr/actualites/2012/06/11/plugin-codehighlight-1.2-tinymce/nCodjLVvyvs4YcukFHq6/)

<pre>
This file is part of tinyMCE.
CodeHighlight for tinyMCE
Copyright (C) 2011 - 2013  Gerits Aurelien aurelien[at]magix-dev[dot]be - contact[at]aurelien-gerits[dot]be

Redistributions of files must retain the above copyright notice.
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see .

####DISCLAIMER

Do not edit or add to this file if you wish to upgrade jimagine to newer
versions in the future. If you wish to customize jimagine for your
needs please refer to magix-dev.be for more information.
</pre>
