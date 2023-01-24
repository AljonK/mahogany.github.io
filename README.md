<!doctype html>
<!--Quite a few clients strip your Doctype out, and some even apply their own. Many clients do honor your doctype and it can make things much easier if you can validate constantly against a Doctype.-->
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Site1</title>

<!-- Please use an inliner tool to convert all CSS to inline as inpage or external CSS is removed by email clients -->
<!-- important in CSS is used to prevent the styles of currently inline CSS from overriding the ones mentioned in media queries when corresponding screen sizes are encountered -->

<style type="text/css">
body {
	margin: 0;
}
body, table, td, p, a, li, blockquote {
	-webkit-text-size-adjust: none!important;
	font-family: sans-serif;
	font-style: normal;
	font-weight: 400;
}
button {
	width: 90%;
}

@media screen and (max-width:600px) {
/*styling for objects with screen size less than 600px; */
body, table, td, p, a, li, blockquote {
	-webkit-text-size-adjust: none!important;
	font-family: sans-serif;
}
table {
	/* All tables are 100% width */
	width: 100%;
}
.footer {
	/* Footer has 2 columns each of 48% width */
	height: auto !important;
	max-width: 48% !important;
	width: 48% !important;
}
table.responsiveImage {
	/* Container for images in catalog */
	height: auto !important;
	max-width: 30% !important;
	width: 30% !important;
}
table.responsiveContent {
	/* Content that accompanies the content in the catalog */
	height: auto !important;
	max-width: 66% !important;
	width: 66% !important;
}
.top {
	/* Each Columnar table in the header */
	height: auto !important;
	max-width: 48% !important;
	width: 48% !important;
}
.catalog {
	margin-left: 0%!important;
}
}

@media screen and (max-width:480px) {
/*styling for objects with screen size less than 480px; */
body, table, td, p, a, li, blockquote {
	-webkit-text-size-adjust: none!important;
	font-family: sans-serif;
}
table {
	/* All tables are 100% width */
	width: 100% !important;
	border-style: none !important;
}
.footer {
	/* Each footer column in this case should occupy 96% width  and 4% is allowed for email client padding*/
	height: auto !important;
	max-width: 96% !important;
	width: 96% !important;
}
.table.responsiveImage {
	/* Container for each image now specifying full width */
	height: auto !important;
	max-width: 96% !important;
	width: 96% !important;
}
.table.responsiveContent {
	/* Content in catalog  occupying full width of cell */
	height: auto !important;
	max-width: 96% !important;
	width: 96% !important;
}
.top {
	/* Header columns occupying full width */
	height: auto !important;
	max-width: 100% !important;
	width: 100% !important;
}
.catalog {
	margin-left: 0%!important;
}
button {
	width: 90%!important;
}
}
</style>
</head>
<body yahoo="yahoo">
<table width="100%"  cellspacing="0" cellpadding="0">
  <tbody>
    <tr>
      <td><table width="600"  align="center" cellpadding="0" cellspacing="0">
          <!-- Main Wrapper Table with initial width set to 60opx -->
          <tbody>
            <tr>
              <td><table bgcolor="#d0cfcf" class="top" width="48%"  align="left" cellpadding="0" cellspacing="0" style="padding:10px 10px 10px 10px;">
                  <!-- First header column with Logo -->
                  <tbody>
                    <tr>
                      <td style="font-size: 12px; color:#929292; text-align:center; font-family: sans-serif;">10 - MAHOGANY</td>
                    </tr>
                  </tbody>
                </table>
                <table bgcolor="#d0cfcf" class="top" width="48%"  align="left" cellpadding="0" cellspacing="0" style="padding:10px 10px 10px 10px; text-align:right">
                  <!-- Second header column with ISSUE|DATE -->
                  <tbody>
                    <tr>
                      <td style="font-size: 12px; color:#929292; text-align:center; font-family: sans-serif;"> MADE WITH DREAMWEAVER T_T</td>
                    </tr>
                  </tbody>
                </table></td>
            </tr>
            <tr> 
              <!-- HTML Spacer row -->
              <td style="font-size: 0; line-height: 0;" height="20"><table width="96%" align="left"  cellpadding="0" cellspacing="0">
                  <tr>
                    <td style="font-size: 0; line-height: 0;" height="20">&nbsp;</td>
                  </tr>
                </table></td>
            </tr>
            <tr> 
              <!-- HTML IMAGE SPACER -->
              <td style="font-size: 0; line-height: 0;" height="20"><table align="left"  cellpadding="0" cellspacing="0" >
                  <tr>
                    <td >&nbsp;</td>
                  </tr>
                </table></td>
            </tr>
            <tr> 
              <!-- HTML Spacer row -->
              <td style="font-size: 0; line-height: 0;" height="20"><table width="96%" align="left"  cellpadding="0" cellspacing="0">
                  <tr>
                    <td style="font-size: 0; line-height: 0;" height="20">&nbsp;</td>
                  </tr>
                </table></td>
            </tr>
            <tr> 
              <!-- Introduction area -->
              <td><table width="96%"  align="left" cellpadding="0" cellspacing="0">
                  <tr> 
                    <!-- row container for TITLE/EMAIL THEME -->
                    <td align="center" style="font-size: 32px; font-weight: 300; line-height: 2.5em; color: #929292; font-family: sans-serif;">10 - Mahogany</td>
                  </tr>
                  <tr> 
                    <!-- row container for Tagline -->
                    <td align="center" style="font-size: 16px; font-weight:300; color: #929292; font-family: sans-serif;">Aljon Kirbey L. Dongallo</td>
                  </tr>
                  <tr>
                    <td style="font-size: 0; line-height: 0;" height="20"><table width="96%" align="left"  cellpadding="0" cellspacing="0">
                        <tr> 
                          <!-- HTML Spacer row -->
                          <td style="font-size: 0; line-height: 0;" height="20">&nbsp;</td>
                        </tr>
                      </table></td>
                  </tr>
                  <tr> 
                    <!-- Row container for Intro/ Description -->
                    <td align="left" style="font-size: 14px; font-style: normal; font-weight: 100; color: #929292; line-height: 1.8; text-align:justify; padding:10px 20px 0px 20px; font-family: sans-serif;">&lt;html&gt; &lt;head&gt; &lt;meta charset="utf-8"&gt; &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt; &lt;title&gt;Site1&lt;/title&gt;&nbsp;&lt;style type="text/css"&gt; body { margin: 0; } body, table, td, p, a, li, blockquote { -webkit-text-size-adjust: none!important; font-family: sans-serif; font-style: normal; font-weight: 400; } button { width: 90%; } @media screen and (max-width:600px) { /*styling for objects with screen size less than 600px; */ body, table, td, p, a, li, blockquote { -webkit-text-size-adjust: none!important; font-family: sans-serif; } table { /* All tables are 100% width */ width: 100%; } .footer { /* Footer has 2 columns each of 48% width */ height: auto !important; max-width: 48% !important; width: 48% !important; } table.responsiveImage { /* Container for images in catalog */ height: auto !important; max-width: 30% !important; width: 30% !important; } table.responsiveContent { /* Content that accompanies the content in the catalog */ height: auto !important; max-width: 66% !important; width: 66% !important; } .top { /* Each Columnar table in the header */ height: auto !important; max-width: 48% !important; width: 48% !important; } .catalog { margin-left: 0%!important; } } @media screen and (max-width:480px) { /*styling for objects with screen size less than 480px; */ body, table, td, p, a, li, blockquote { -webkit-text-size-adjust: none!important; font-family: sans-serif; } table { /* All tables are 100% width */ width: 100% !important; border-style: none !important; } .footer { /* Each footer column in this case should occupy 96% width and 4% is allowed for email client padding*/ height: auto !important; max-width: 96% !important; width: 96% !important; } .table.responsiveImage { /* Container for each image now specifying full width */ height: auto !important; max-width: 96% !important; width: 96% !important; } .table.responsiveContent { /* Content in catalog occupying full width of cell */ height: auto !important; max-width: 96% !important; width: 96% !important; } .top { /* Header columns occupying full width */ height: auto !important; max-width: 100% !important; width: 100% !important; } .catalog { margin-left: 0%!important; } button { width: 90%!important; } } &lt;/style&gt; &lt;/head&gt; &lt;body yahoo="yahoo"&gt; &lt;table width="100%" cellspacing="0" cellpadding="0"&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td&gt;&lt;table width="600" align="center" cellpadding="0" cellspacing="0"&gt; &lt;!-- Main Wrapper Table with initial width set to 60opx --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td&gt;&lt;table bgcolor="#d0cfcf" class="top" width="48%" align="left" cellpadding="0" cellspacing="0" style="padding:10px 10px 10px 10px;"&gt; &lt;!-- First header column with Logo --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td style="font-size: 12px; color:#929292; text-align:center; font-family: sans-serif;"&gt;10 - MAHOGANY&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt; &lt;table bgcolor="#d0cfcf" class="top" width="48%" align="left" cellpadding="0" cellspacing="0" style="padding:10px 10px 10px 10px; text-align:right"&gt; &lt;!-- Second header column with ISSUE|DATE --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td style="font-size: 12px; color:#929292; text-align:center; font-family: sans-serif;"&gt; MADE WITH DREAMWEAVER T_T&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;tr&gt; &lt;!-- HTML Spacer row --&gt; &lt;td style="font-size: 0; line-height: 0;" height="20"&gt;&lt;table width="96%" align="left" cellpadding="0" cellspacing="0"&gt; &lt;tr&gt; &lt;td style="font-size: 0; line-height: 0;" height="20"&gt;&nbsp;&lt;/td&gt; &lt;/tr&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;tr&gt; &lt;!-- HTML IMAGE SPACER --&gt; &lt;td style="font-size: 0; line-height: 0;" height="20"&gt;&lt;table align="left" cellpadding="0" cellspacing="0" &gt; &lt;tr&gt; &lt;td &gt;&nbsp;&lt;/td&gt; &lt;/tr&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;tr&gt; &lt;!-- HTML Spacer row --&gt; &lt;td style="font-size: 0; line-height: 0;" height="20"&gt;&lt;table width="96%" align="left" cellpadding="0" cellspacing="0"&gt; &lt;tr&gt; &lt;td style="font-size: 0; line-height: 0;" height="20"&gt;&nbsp;&lt;/td&gt; &lt;/tr&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;tr&gt; &lt;!-- Introduction area --&gt; &lt;td&gt;&lt;table width="96%" align="left" cellpadding="0" cellspacing="0"&gt; &lt;tr&gt; &lt;!-- row container for TITLE/EMAIL THEME --&gt; &lt;td align="center" style="font-size: 32px; font-weight: 300; line-height: 2.5em; color: #929292; font-family: sans-serif;"&gt;10 - Mahogany&lt;/td&gt; &lt;/tr&gt; &lt;tr&gt; &lt;!-- row container for Tagline --&gt; &lt;td align="center" style="font-size: 16px; font-weight:300; color: #929292; font-family: sans-serif;"&gt;Aljon Kirbey L. Dongallo&lt;/td&gt; &lt;/tr&gt; &lt;tr&gt; &lt;td style="font-size: 0; line-height: 0;" height="20"&gt;&lt;table width="96%" align="left" cellpadding="0" cellspacing="0"&gt; &lt;tr&gt; &lt;!-- HTML Spacer row --&gt; &lt;td style="font-size: 0; line-height: 0;" height="20"&gt;&nbsp;&lt;/td&gt; &lt;/tr&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;tr&gt; &lt;!-- Row container for Intro/ Description --&gt; &lt;td align="left" style="font-size: 14px; font-style: normal; font-weight: 100; color: #929292; line-height: 1.8; text-align:justify; padding:10px 20px 0px 20px; font-family: sans-serif;"&gt;&lt;html&gt; &lt;head&gt; &lt;meta charset="utf-8"&gt; &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt; &lt;title&gt;Site1&lt;/title&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;tr&gt; &lt;!-- HTML Spacer row --&gt; &lt;td style="font-size: 0; line-height: 0;" height="10"&gt;&lt;table width="96%" align="left" cellpadding="0" cellspacing="0"&gt; &lt;tr&gt; &lt;td style="font-size: 0; line-height: 0;" height="20"&gt;&nbsp;&lt;/td&gt; &lt;/tr&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;tr&gt; &lt;td&gt;&lt;table cellpadding="0" cellspacing="0" align="center" width="84%" style="margin-left:12.5%" class="catalog"&gt; &lt;!-- Table for catalog --&gt; &lt;tr&gt; &lt;td &gt;&lt;table class ="responsive-table" width="48%" cellspacing="0" cellpadding="0" align="left" style="margin: 10px 0px 10px 0px;"&gt; &lt;!-- Table container for each image and description in catalog --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td&gt;&lt;table class="table.responsiveImage" width="66%" cellspacing="0" cellpadding="0" align="left"&gt; &lt;!-- Table container for image --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td align="center" style="padding:10px 3px 10px 3px;"&gt;&lt;img src="file:///C|/Users/user/AppData/Roaming/Adobe/Dreamweaver CC 2018/en_US/Configuration/Temp/Assets/eam81A3.tmp/images/120x120.gif" alt="sample" style="width: 120px;"&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt; &lt;table class="table.responsiveContent" width="66%" cellspacing="0" cellpadding="0" align="left"&gt; &lt;!-- Table container for content --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td&gt;&lt;p style="font-size: 14px; font-style: normal; font-weight: normal; color: #929292; padding: 5px 0px 0px 10px;line-height: 1.5em; font-family: sans-serif;"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus congue metus&lt;/p&gt; &lt;a href="#" style="text-decoration:none"&gt; &lt;p style="background-color:#AAAAAA; text-align:center; padding: 10px 10px 10px 10px; margin: 10px 10px 10px 10px;color: #FFFFFF; font-family: sans-serif; "&gt;Read More&lt;/p&gt; &lt;/a&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt; &lt;table class ="responsive-table" width="48%" cellspacing="0" cellpadding="0" align="left" style="margin: 10px 0px 10px 0px;"&gt; &lt;!-- Table container for each image and description in catalog --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td&gt;&lt;table class="table.responsiveImage" width="66%" cellspacing="0" cellpadding="0" align="left"&gt; &lt;!-- Table container for image --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td align="center" style="padding:10px 3px 10px 3px;"&gt;&lt;img src="file:///C|/Users/user/AppData/Roaming/Adobe/Dreamweaver CC 2018/en_US/Configuration/Temp/Assets/eam81A3.tmp/images/120x120.gif" alt="sample" style="width: 120px;"&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt; &lt;table class="table.responsiveContent" width="66%" cellspacing="0" cellpadding="0" align="left"&gt; &lt;!-- Table container for content --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td&gt;&lt;p style="font-size: 14px; font-style: normal; font-weight: normal; color: #929292; padding: 5px 0px 0px 10px;line-height: 1.5em; font-family: sans-serif;"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus congue metus&lt;/p&gt; &lt;a href="#" style="text-decoration:none"&gt; &lt;p style="background-color:#AAAAAA; text-align:center; padding: 10px 10px 10px 10px; margin: 10px 10px 10px 10px;color: #FFFFFF; font-family: sans-serif; "&gt;Read More&lt;/p&gt; &lt;/a&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;tr&gt; &lt;td&gt;&lt;table class ="responsive-table" width="48%" cellspacing="0" cellpadding="0" align="left" style="margin: 10px 0px 10px 0px;"&gt; &lt;!-- Table container for each image and description in catalog --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td&gt;&lt;table class="table.responsiveImage" width="66%" cellspacing="0" cellpadding="0" align="left"&gt; &lt;!-- Table container for image --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td align="center" style="padding:10px 3px 10px 3px;"&gt;&lt;img src="file:///C|/Users/user/AppData/Roaming/Adobe/Dreamweaver CC 2018/en_US/Configuration/Temp/Assets/eam81A3.tmp/images/120x120.gif" alt="sample" style="width: 120px;"&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt; &lt;table class="table.responsiveContent" width="66%" cellspacing="0" cellpadding="0" align="left"&gt; &lt;!-- Table container for content --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td&gt;&lt;p style="font-size: 14px; font-style: normal; font-weight: normal; color: #929292; padding: 5px 0px 0px 10px;line-height: 1.5em; font-family: sans-serif;"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus congue metus&lt;/p&gt; &lt;a href="#" style="text-decoration:none"&gt; &lt;p style="background-color:#AAAAAA; text-align:center; padding: 10px 10px 10px 10px; margin: 10px 10px 10px 10px;color: #FFFFFF; font-family: sans-serif;"&gt;Read More&lt;/p&gt; &lt;/a&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt; &lt;table class ="responsive-table" width="48%" cellspacing="0" cellpadding="0" align="left" style="margin: 10px 0px 10px 0px;"&gt; &lt;!-- Table container for each image and description in catalog --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td&gt;&lt;table class="table.responsiveImage" width="66%" cellspacing="0" cellpadding="0" align="left"&gt; &lt;!-- Table container for image --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td align="center" style="padding:10px 3px 10px 3px;"&gt;&lt;img src="file:///C|/Users/user/AppData/Roaming/Adobe/Dreamweaver CC 2018/en_US/Configuration/Temp/Assets/eam81A3.tmp/images/120x120.gif" alt="sample" style="width: 120px;"&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt; &lt;table class="table.responsiveContent" width="66%" cellspacing="0" cellpadding="0" align="left"&gt; &lt;!-- Table container for content --&gt; &lt;tbody&gt; &lt;tr&gt; &lt;td&gt;&lt;p style="font-size: 14px; font-style: normal; font-weight: normal; color: #929292; padding: 5px 0px 0px 10px;line-height: 1.5em; font-family: sans-serif;"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus congue metus&lt;/p&gt; &lt;a href="#" style="text-decoration:none"&gt; &lt;p style="background-color:#AAAAAA; text-align:center; padding: 10px 10px 10px 10px; margin: 10px 10px 10px 10px;color: #FFFFFF; font-family: sans-serif;"&gt;Read More&lt;/p&gt; &lt;/a&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;tr&gt; &lt;!-- HTML spacer row --&gt; &lt;td style="font-size: 0; line-height: 0;" height="20"&gt;&lt;table width="96%" align="left" cellpadding="0" cellspacing="0"&gt; &lt;tr&gt; &lt;td style="font-size: 0; line-height: 0;" height="20"&gt;&nbsp;&lt;/td&gt; &lt;/tr&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;tr bgcolor="#d0cfcf"&gt; &lt;td&gt;&lt;table class="footer" width="48%" align="left" cellpadding="0" cellspacing="0"&gt; &lt;!-- First column of footer content --&gt; &lt;tr&gt; &lt;td&gt;&lt;p align="center" style="font-size: 22px; font-weight:300; line-height: 2.5em; color: #929292; font-family: sans-serif;"&gt;COMPANY NAME&lt;/p&gt; &lt;p align="center" style="font-size: 12px; color:#929292; text-align:center; font-family: sans-serif;"&gt;SOME AWESOME TAGLINE&lt;/p&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/table&gt; &lt;table class="footer" width="48%" align="left" cellpadding="0" cellspacing="0"&gt; &lt;!-- Second column of footer content --&gt; &lt;tr&gt; &lt;td&gt;&lt;p style="font-size: 14px; font-style: normal; font-weight:normal; color: #ffffff; line-height: 1.8; text-align:justify;padding-top:10px; margin-left:20px; margin-right:20px; font-family: sans-serif;"&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus congue metus quam, eu luctus risus tincidunt ultrices. Mauris interdum magna ut orci tempus feugiat. &lt;/p&gt; &lt;p align="right" style="font-family: sans-serif;"&gt; &lt;a style="color:#929292; text-decoration:none; padding-left:20px; font-size:14px;" href="#"&gt;Link 1&lt;/a&gt; &lt;a style="color:#929292; text-decoration:none; padding-left:20px; font-size:14px;" href="#"&gt;Link 2&lt;/a&gt; &lt;a style="color:#929292; text-decoration:none; font-size:14px; padding-left:20px; padding-right:20px; " href="#"&gt;Link 3&lt;/a&gt;&lt;/p&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt;&lt;/td&gt; &lt;/tr&gt; &lt;/tbody&gt; &lt;/table&gt; &lt;/body&gt; &lt;/html&gt; </td>
                  </tr>
                </table></td>
            </tr>
            <tr> 
              <!-- HTML Spacer row -->
              <td style="font-size: 0; line-height: 0;" height="10"><table width="96%" align="left"  cellpadding="0" cellspacing="0">
                  <tr>
                    <td style="font-size: 0; line-height: 0;" height="20">&nbsp;</td>
                  </tr>
                </table></td>
            </tr>
            <tr> </tr>
            <tr> 
              <!-- HTML spacer row -->
              <td style="font-size: 0; line-height: 0;" height="20"><table width="96%" align="left"  cellpadding="0" cellspacing="0">
                  <tr>
                    <td style="font-size: 0; line-height: 0;" height="20">&nbsp;</td>
                  </tr>
                </table></td>
            </tr>
            <tr bgcolor="#d0cfcf">
              <td><table class="footer" width="48%"  align="left" cellpadding="0" cellspacing="0">
                  <!-- First column of footer content -->
                  <tr>
                    <td><p align="center" style="font-size: 22px; font-weight:300; line-height: 2.5em; color: #929292; font-family: sans-serif;">RECORDING YOUR DATA</p>
                    <p align="center" style="font-size: 12px; color:#929292; text-align:center; font-family: sans-serif;">ALJON KIRBEY L. DONGALLO</p></td>
                  </tr>
                </table>
                <table class="footer" width="48%"  align="left" cellpadding="0" cellspacing="0">
                  <!-- Second column of footer content -->
                  <tr>
                    <td><p>PLEASE DO NOT PUBLICLY ANNOUNCE YOUR PERSONAL EMAIL OR PHONE NUMBER I AM A VICTIM OF EXTORTION SCAM I RECOMMEND CREATING AN EMAIL FOR BUSINESS USE SO DO NOT USE YOUR PERSONAL EMAIL FOR EVERYTHING</p>                      <p align="right" style="font-family: sans-serif;"> <a style="color:#929292; text-decoration:none; padding-left:20px; font-size:14px;" href="#">Link 1</a> <a style="color:#929292; text-decoration:none; padding-left:20px;  font-size:14px;" href="#">Link 2</a> <a style="color:#929292; text-decoration:none; font-size:14px; padding-left:20px; padding-right:20px; " href="#">Link 3</a></p></td>
                  </tr>
                </table></td>
            </tr>
          </tbody>
        </table></td>
    </tr>
  </tbody>
</table>
</body>
</html>
