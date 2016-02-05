# dragDrop
Basic Drag and Drop

1. Create a Drop-zone that blocks drops and prevents default on the rest of the page.
 with:   e.preventDefault();

2. Drop-zone in the center changes color when hovered on.
 with: dropzone.className += ' onTop';
 and:
    if ($(".dropzone").hasClass("onTop")) {
        $(".dropzone").removeClass("onTop")
    }
    
3. Control mouse icon upon drag-n-drop  
e.dataTransfer.dropEffect = "copy";
e.dataTransfer.dropEffect = "none";

4. Load file in Drag and Drop
