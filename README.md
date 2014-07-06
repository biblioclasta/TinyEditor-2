# TinyEditor 2
## based on TinyEditor by: [Michael Leigeber](http://www.scriptiny.com/author/michael/)


TinyEditor is a simple JavaScript WYSIWYG editor that is both lightweight (8KB) and standalone. It can easily be customized to integrate with any website through CSS and the multitude of parameters. It handles most of the basic formatting needs and has some functionality built in to help keep the rendered markup as clean as possible. The icons are courtesy of famfamfam and have been combined into a sprite so there are only a few HTTP requests for the editor. I plan on adding some updates in the future to support font color, a full-screen mode, and a paste from Word option.



I've used this simple editor for some time and I love it. It's lightweight and it gets the job done. As I use it more, I've come to find out that I need to hack it and thus I've got a need to fork it. Unfortunately this does not appear to be a part of any official github repository.

![JavaScript WYSIWYG Editor](http://www.scriptiny.com/wp-content/uploads/2010/02/editor.jpg "JavaScript WYSIWYG Editor")

    new TinyEditor({
        el:'#input', // Query of the textarea
        width:584, // (optional) width of the editor
        height:175, // (optional) heightof the editor
        controls:['bold', 'italic', 'underline', 'strikethrough', '|', 'subscript', 'superscript', '|', 'orderedlist', 'unorderedlist', '|' ,'outdent' ,'indent', '|', 'leftalign', 'centeralign', 'rightalign', 'blockjustify', '|', 'unformat', '|', 'undo', 'redo', 'n', 'font', 'size', 'style', '|', 'image', 'hr', 'link', 'unlink', '|', 'cut', 'copy', 'paste', 'print'], // (required) options you want available, a '|' represents a divider and an 'n' represents a new row
        footer:true, // (optional) show the footer
        fonts:['Verdana','Arial','Georgia','Trebuchet MS'],  // (optional) array of fonts to display
        toggle:{text:'source',activetext:'wysiwyg',cssclass:'toggle'}, // (optional) toggle to markup view options
        resize:{cssclass:'resize'} // (optional) display options for the editor resize
    });

This script has been tested in all major browsers and is available free of charge for both personal or commercial projects under the [creative commons license](http://creativecommons.org/licenses/by/3.0/us/).
