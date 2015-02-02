# jSignature Jpeg PNG plugin

This project creates a plug-in to render JPEG (JPG) and PNG images from vectors just like the back-end process except it does so in JavaScript on the client.

Modern Mobile App platforms and browsers have the capability to render the signatures to images directly. The plug-in created in this project does that. The plug-in renders an image independent of the jSignature capture size and without the decorations. 

To tryout this plug-in in context go to my jSignature fork and look in the directories listed below. 
https://github.com/mountaintom/jSignature

In the examples directory the unmini.html demo file has been modified to demonstrate this new (jSignature.CompressorRenderedImage.js) plug-in.

####The following items are configurable for the plugin:

		RIwidth [Size of rendered image width. Default 300 pixels]
		RIheight  [Size of rendered image height. Default 150 pixels]
		RIcolor [Color of line. Default #000 (Black)]
		RIbackground-color-jpeg [Default #fff (White)]		
		RIbackground-color-png [Default transparent]
		RIlineWidth [Default 3 pixels]

####Example configuration:
$(“#signature”).jSignature({‘color’:’#00f’, 'UndoButton':true, 'RIcolor':'green', ‘RIbackground-color-png':'#eee'}

This sets the jSignature pad line color to blue with an Undo button. The image will be rendered with a green line and if the image is rendered as a PNG the background will be a light grey

--Tom   mtm{removethis}@mountaintom.com


