
1) $('.profile-image').attr('src','http://vignette2.wikia.nocookie.net/villains/images/0/01/Mr.png/revision/latest?cb=20160819130204')

$('#left-image').children('img').attr('src', 'http://vignette2.wikia.nocookie.net/villains/images/0/01/Mr.png/revision/latest?cb=20160819130204');


2) $(".highlight").text('Assignment')


3) var i = $('.info-title')[1]
<h3 class=​"info-title">​…​</h3>​
var icon = $('.info-title')[1].children[0]
$(icon).appendTo(i)
[i.icon-suitcase]
$(i).append("unemployed")

4)  $('#time-travel').parent().remove()

5) $('body').css("background-color","red")

6) ('.highlight').css("color","blue")

7) $('h1').css("font-family","monospace")

8) $('.action-icon-bg').css('background-color', 'blue')

9) $('#name').attr('placeholder', "identify yourself")

10) $('#message').attr('placeholder', 'state your business')

11) $('#name').attr('placeholder', "Douche-a-tron 5000")

12) $('#email').attr('placeholder', 'koalathebear@gmail.com')

13) $('#submit').attr('value', 'Defcon')

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
