# dragDrop
Basic Drag and Drop

- Create a Drop-zone that blocks drops and prevents default on the rest of the page.
 with:   e.preventDefault();

- Drop-zone in the center changes color when hovered on.
 with: 

```
dropzone.className += ' onTop';
```

 and:
 
 ```
    if ($(".dropzone").hasClass("onTop")) {
        $(".dropzone").removeClass("onTop")
    }
 ```
    
- Control mouse icon upon drag-n-drop  

```
e.dataTransfer.dropEffect = "copy";
e.dataTransfer.dropEffect = "none";
```

- Load file in Drag and Drop
