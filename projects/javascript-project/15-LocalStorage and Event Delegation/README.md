# localstorage-event-delegation

Day/Lesson #15 from [Wes Bos'](http://wesbos.com/) free [JavaScript 30](https://javascript30.com/) course where you use vanilla JS

In this lesson I learned about event delegation in order to handle situations where new elements are added to something like a `<ul>`
and you need to handle click events on those elements but since they do not exist when the page loads you cannot include them in a
`document.querySelectorAll()` / `.forEach()` / `addEventListener()` kind of loop.