#LJ Code 201 - Day 14

#Functions

Working on quiz 7 (without any redos!) really made me wrestle down an understanding of how to construct a function, and it was the first time that I felt comfortable in using the console on a blank page to try different variables/parameters etc out in order to solve the problem. Or at least come close :)

My code had all dogs saying 'bark', then I reassigned Parker's bark to 'woof', but it would have been better to have a separate function so that I didn't have ALL the dogs saying 'bark':

Dog.prototype.says = function(bark) {
  console.log(this.name + ' says ' + bark);
};
