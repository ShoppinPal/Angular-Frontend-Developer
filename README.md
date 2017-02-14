# Angular-Frontend-Developer
Practical Test for the position of Angular Frontend Developer

# Test

This test requires you to demonstrate the ability to learn and deliver, which is what we do at ShoppinPal on a daily basis:

1. Create an application by using loopback.io as the backend server. The project to work on is available here: https://github.com/ShoppinPal/Frontend-Test-Project
    * The Loopback API server is built on top of the Express web server which is well known in the Node.js community.
2. You may use any front end framework like angular js and CSS framework like bootstrap or materializeCSS to make your work easy. Any custom CSS work should be done with `SASS` only.
3. Your application should have an attractive signup and login page.
    * This is where your UI/UX skillset also shines, so be simple and creative.
    * After login, the username should show on the page somewhere indicating who has logged in.
4. Directly trying to access any internal page should redirect it back to login if unauthenticated and any authenticated user shouldn’t see login page.
5. Your application should work with the memory connector in loopback. You don't need a database.
6. Your application should allow the logged-in user to create a category. Editing and deleting a category should also be possible.
    * You need to have dynamic dom manipulation in add category form where input fields are created dynamically based on prior selected element in the form.
        * This is again your chance to showcase your UI/UX skillset.
        * Keep it simple, functional and beautiful.
    * If angular is used then showcase of directives, services and components will be a big plus.
User should be able to search for existing categories by providing a typeahead match on leading characters. Your list view of categories should have lazy loading applied to it (as we scroll elements are loaded). Your views should have common headers and footer throughout the code with breadcrumbs to help navigate to previous page or parent page. 
eg: category > edit category


Extra toppings: (It’s not mandatory but candidate who does this will have a huge probability of getting selected )
User should be able to drill down into a detailed view for a selected category and add a parent category or a child category or both. Users should not add any new categories, they should use those that have already been created for mapping. 
