
#Combobox

First things first, this whole project is based off of a YouTube video
   by Designmodo (http://designmodo.com/),
   Part1: https://www.youtube.com/watch?v=tyLlKwBrivQ
   Part2: https://www.youtube.com/watch?v=F1eIZMkgeAU

#TLDR

Combobox does this

select -> ul w/textbox & Autocomplete

after you do this

$('#mySelectElement').combobox();

#What does it do?

This jQuery UI widget transforms select elements into Unordered Lists. This list is presented as a textbox and a dropdown with Autocomplete.

#How to use

Do this to initialize the combobox.

    $('#mySelectElement').combobox();


#Extras

Want the list closed when you first initialize the combobox?
Pass in {isOpen: false} like this

$('#mySelectElement').combobox({isOpen: false});

Want to change the textbox text?
Pass in {textBoxText: 'Howdy do'} like this

$('#mySelectElement').combobox({textBoxText: 'Howdy do'});

Want to show the text of the element in the textbox and not the value?
Pass in {showText: true} like this

$('#mySelectElement').combobox({showText: true});
