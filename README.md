
#Combobox

First things first, this whole project is based off of a YouTube video by Designmodo (http://designmodo.com/),

   Part1: https://www.youtube.com/watch?v=tyLlKwBrivQ

   Part2: https://www.youtube.com/watch?v=F1eIZMkgeAU

#TLDR

Combobox does this

![Alt text](/Screenshot.jpg?raw=true "Screenshot")

select -> ul w/textbox & autocomplete

after you do this

    $('#mySelectElement').combobox();

#What does it do?

This jQuery UI widget transforms select elements into Unordered Lists. This list is presented as a textbox and a dropdown with autocomplete.

#How to use

Do this to initialize the combobox.

    $('#mySelectElement').combobox();


#Extras

Want the list closed when you first initialize the combobox?
Pass in ```{isOpen: false}``` like this

    $('#mySelectElement').combobox({isOpen: false});

Want to change the textbox text?
Pass in ```{textBoxText: 'Howdy do'}``` like this

    $('#mySelectElement').combobox({textBoxText: 'Howdy do'});

Want to show the text of the element in the textbox and not the value?
Pass in ```{showText: true}``` like this

    $('#mySelectElement').combobox({showText: true});

Want to use an icon instead of text for the button?
Pass in ```{useIcon: '<i class="fa fa-bars"></i>'}``` like this

    $('#mySelectElement').combobox({useIcon: '<i class="fa fa-bars"></i>'});
^^^^^^^ Make sure you can render that font. in this example you'd need
FontAwesome (http://FontAwesome.com) for this font to actually show up
