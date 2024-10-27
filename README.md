How to add a PDF:

1. Upload PDF file
2. Copy & paste any index file and insert new PDF file name under title and the filename at the end of the iframe URL: 
" <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html lang="en" style="width:100%; height:100%;">
<head>
  <meta http-equiv="content-type" content="text/html; charset=utf-8">
  <title>PAPER TITLE HERE</title>
</head>
  <body style="width:100%; height:100%; margin:0;">
    <iframe src="https://docs.google.com/gview?url= https://github.com/jonmeer/papers/blob/main/PDFNAME.pdf &embedded=true" style="width:100%; height:100%;" frameborder="0"></iframe>
  </body>
</html> "

3. Save above as index_name.html
4. Link new paper as: https://github.com/jonmeer/papers/blob/main/PDFNAME.pdf



How to update a PDF:
1. Upload PDF under exact same file name & commit the change
