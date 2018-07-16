Part 1
1. Element that contains the profile image
var image = document.querySelector('img')
image.src =  "https://assets.change.org/photos/9/vb/ck/SjvBckptvTHTuGQ-400x400-noPad.jpg?1509404753"

2. var sky = document.querySelector('.portfolio-image > img');
sky.src = 'http://marketbuffet.com/wp-content/uploads/2017/01/Unknown-4-325x255.jpg'

3. Select the heading that says "Panda the Bear" and change it to your own name.
var banner = document.querySelector('h1');
banner.innerHTML = 'Yumee Lee'

4. Select the heading that says "Employment" and change it to something else.
var employment = document.querySelector('#employment > h3');
employment.innerHTML = 'Sleeping'

5. Change the colour of the body.
var newcolor = document.body
newcolor.style.color = '#e6ffe6';

6. Change the colour of each element using the highlight class. Use a for loop to do this.
  var highlight = document.querySelectorAll('.highlight')
  for (var i = 0; i < highlight.length; i++) {
    highlight[i].style.color = 'pink'
  };

7. Change the font family of the h1 to 'monospace'.
  monospace = document.querySelector('h1.highlight')
  monospace.style.fontFamily = 'monospace';

8. Find a way to select the round icons in the sidebar and then change their colour.
  var containers = document.querySelectorAll('.action-icon-bg')
  containers.forEach(function(container) {
    container.style.backgroundColor = 'black'
    });

9.a. Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself".
  var identify = document.querySelector('#name')
  identify.placeholder = 'Identify yourself'

9.b. Change the placeholder attribute of the message field to "state your business".
 var business = document.querySelector('#message')
 business.placeholder = 'State your business'

10. Give the name field a "value" attribute of "your nemesis".
  identify.value = 'your nemesis'

11. Change the value attribute of the email field to "koalathebear@gmail.com".
  koala.value = 'koalathebear@gmail.com'

12. Change the value of the submit button on the contact form to "En garde!".
  var subButton = document.querySelector('#submit')
  subButton.value = 'En garde!'

13. We should stop Koala from sending an email to Panda that they might regret! Find a way to disable the submit button (hint: familiarize yourself with the disabled attribute).
  document.getElementById('submit').disabled = true

14. We should help Panda protect their privacy by erasing their personal details from the sidebar.
var sidebarInfo = document.querySelector('.bio-info')
sidebarInfo.remove()

Part 2
1. Removing elements from the DOM
var bar = document.querySelector('#time-travel')
bar.parentNode.remove()

2.  Adding elements
var pikachu = document.querySelector('#right-image');
var pikachuCopy = pikachu.firstElementChild;
var PikachuClone = pikachuCopy.cloneNode();
var portfolio = document.querySelector('div.portfolio-container');
portfolio.appendChild(PikachuClone);

3. Use a for loop to help you do this 10 times.
