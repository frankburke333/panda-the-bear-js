<!-- 1) Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead (hint: use attr()). -->

$('.profile-image').attr('src','http://vignette2.wikia.nocookie.net/villains/images/0/01/Mr.png/revision/latest?cb=20160819130204')

$('#left-image').children('img').attr('src', 'http://vignette2.wikia.nocookie.net/villains/images/0/01/Mr.png/revision/latest?cb=20160819130204');

<!-- 2 Select the heading that says "Panda the Bear" and change it to your own name. (hint: use text()) -->

$(".highlight").text('Assignment')

<!-- 3 Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector) -->

var i = ('.info-title')[1]
undefined
i
"i"
var i = $('.info-title')[1]
undefined
i
<h3 class=​"info-title">​…​</h3>​
var icon = $('.info-title')[1]children[0]
VM10220:1 Uncaught SyntaxError: Unexpected identifier
var icon = $('.info-title')[1].children[0]
undefined
icon
<i class=​"icon-suitcase">​…​</i>​
i.innerHTML = ""
""
$(icon).appendTo(i)
[i.icon-suitcase]
$(i).append("unemployed")

<!-- 4 Panda the Bear is lying about their skills! Take the "time travel" skill off the page to satisfy your personal sense of justice. Use your googling and docs-skimming skillz to find a jQuery function that will allow you to remove elements from the DOM. (hint: there are multiple ways of doing this, but the parent() function might be useful when it comes to selecting the right element) -->

$('#time-travel').parent().remove()

<!-- 5) Change the colour of the body. (hint: use css()) -->


$('body').css("background-color","red")

<!-- 6) Change the colour used by the highlight class. -->


$('.highlight').css("color","blue")


<!-- 7) Change the font family of the h1 to 'monospace'. -->

$('h1').css("font-family","monospace")

<!-- 8) Find a way to select the round icons in the sidebar and then change their colour. -->

$('.action-icon-bg').css('background-color', 'blue')

<!-- 9) Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself". -->

$('#name').attr('placeholder', "identify yourself")

<!-- 10) Change the placeholder attribute of the message field to "state your business". -->
$('#message').attr('placeholder', 'state your business')

<!-- 11) Give the name field a "value" attribute of "your nemesis". -->
$('#name').attr('placeholder', "Douche-a-tron 5000")

<!-- 12) Change the value attribute of the email field to "koalathebear@gmail.com". -->
$('#email').attr('placeholder', 'koalathebear@gmail.com')

<!-- 13) Change the value of the submit button on the contact form to "En garde!". -->
$('#submit').attr('value', 'Defcon')

Bonus
$('.bio-info-location').empty()
[span.bio-info-value.bio-info-location]
$('.bio-info-name').empty()
[span.bio-info-value.bio-info-name]
$('.bio-info-phone').empty()

Pikachu
for (var i = 0; i < 10; i++) {$ ('#right-image').clone().insertAfter('form')}
[div#right-image.portfolio-image]


var listItem = document.createElement('li'); //create a new tag var leftSpan = document.createElement('span'); var rightSpan = document.createElement('span'); //make a "text node" in order to put text inside our new span var lastUpdated = document.createTextNode('Page last updated on'); var today = document.createTextNode('2017/2/14');
leftSpan.appendChild(lastUpdated); rightSpan.appendChild(today);

listItem.appendChild(leftSpan); listItem.appendChild(rightSpan);

var bio = document.getElementsByClassName('bio-info'); bio[0].appendChild(listItem);
