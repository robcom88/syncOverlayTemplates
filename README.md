Building Overlay Templates

From Scratch (i.e. hand-crafting html from a visual design (png, jpg, etc.))

Use the template_framework.html file as a starting point.
	Set stylesheet references to the different css files that will be used
		usually:  	syncbootstrap.css (namespaced bootstrap library)
					overlaybase.css (minimal styles for overlay containers)
					{custom theme stylesheet}   (your new stylesheet if you want something different)
		
	Build the html within the <!-- template start -->/<!-- template end --> comments
	
	Once it looks right, "tokenize" the variable elements of the overlay (copy, images, etc.)
	
	Compile the stylesheets into one via LESS

	Create any Plan templates
		This part is hard.  The html can be crafted/tuned in the framework but then must be 
		extracted, encoded (quotes and other JSON-specific chars escaped),
		and POSTED via API to get it in place
	
	Get the templates loaded to admin tool
		DB Script for new defaults?
	
	
