# Calendar
Calendar is populated with javascript Slight bug :/
If you go forward one month and click a cell putting event doesnt work 

@anyone How do i get my method 
(function() {

var titles = document.querySelectorAll(".cld-day");
var i = titles.length;
while (i--) {
    titles[i].setAttribute("onclick", "mysFunction()");
}

})();

to set the attribute onclick to every li element when the user goes to next month?

