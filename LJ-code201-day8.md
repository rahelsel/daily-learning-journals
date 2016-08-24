#LJ Code 201 - Day 8

#Review of Objects

var obj = {
  name: 'Brian'
}

obj

obj.newProperty = 'some new value for our new property'

obj

#Make a constructor:

function Course(title, studentCount) {
  this.title = title;
  this.studentCount = studentCount;
}

var code_201 = new Course(201, 6);

#Forms

When styling the buttons on your form, use:
- text shadow to give a 3d look to the text
- border bottom can make the bottom border thicker and more 3D
- the pseudo class hover to change the look of the button when the user hovers over it
