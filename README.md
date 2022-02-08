# Form a Story

Forms are great for collecting information on users, like job applications or insightful surveys. However, we can also stretch our creative muscles and have a little fun with forms. For this project, we’ll use our knowledge of the HTML `<form>` and grab user input to put a spin on a classic story!

The logic for parsing and inserting of user inputs is already taken care of in **main.js** using JavaScript . We’ve also added some styling to the page in **style.css.** You can find these files by click on the folder icon located at the top of the code editor and selecting the files you’re interested in.

What you have to do is now make a `<form>` capable of collecting the correct information so that the newly crafted story makes sense!

Note: Save your code as you follow the steps to see your progress!

- [] 1. We’ll be collecting information from our users using a `<form>` so, first, we have to add a `<form>` under the `<hr>` element inside the `<body>` of **index.html.**

- [] 2. Assign `<form>` an `action` of `"story.html"` and a `method` of `"GET"`.
We'll be sending information from out form to **story.html** using a GET request.

- [] 3. In the `<form>`, create a submit button by adding an `<input>` with a `type` of `"submit"`. Assign
the `value` a value of `"Form My Story!"`. Save your code to see the button rendered.