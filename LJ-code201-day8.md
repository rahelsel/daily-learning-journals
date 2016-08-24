#LJ Code 201 - Day 8

#Review of Objects

var obj = {
  name: 'Brian'
}

obj

obj.newProperty = 'some new value for our new property'

obj

#Make a constructor:

>function Course(title, studentCount) {
>  this.title = title;
>  this.studentCount = studentCount;
>}

var code_201 = new Course(201, 6);

#Forms

<form>
  <input type = "text"> //defines the type of form element
  <input type = "text" placeholder="enter more">

</form>

#Form Code:
<button id="toggler">Click Me!</button>
//when someone clicks on this button, we need something to happen so://
JS
<var btn = document.getElementByID('toggler');
btn.addEventListener('click', function()) {
  alert('clicked button')
}
