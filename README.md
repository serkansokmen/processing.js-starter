**This project is no longer maintained.** You may be interested in [p5js](https://p5js.org/).

# Processing.js starter kit

1. Create a separate Processing file or files, naming them whatever you want, as long as they have a *.pde extension.
2. Include Processing filenames as a space-separated list in a data-processing-sources attribute on the canvas.
3. Processing.js will automatically scan the document on page load for <canvas> elements with data-processing-sources attributes, download the files using XMLHTTPRequest, and feed them to the Processing-to-JavaScript translator. The resulting JavaScript is run using eval.
4. To change canvas size:
	- edit ".processingcanvas" class in "css/style.css".
	- edit *.pde file's "size()" function in "void setup()" on line 4.
