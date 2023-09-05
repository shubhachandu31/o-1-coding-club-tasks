# o-1-coding-club-tasks
SDE Internship Task 1 

1. CREATE A NEW HTML PAGE NAMED "task.html"
   Create your HTML page (task.html) in the app's templates folder.
2. CREATE A BASIC CSS FILE NAMED "style.css"
   CSS file (style.css) in the same folder.
   Make sure the HTML page includes the {% load static %} template tag and references the CSS file using the {% static %} template.
3. WE NEED A NEW URL localhost:8000/url/task.
   Define URL Patterns:
   In your app's urls.py file, define a URL pattern for the desired URL (localhost:8000/url/task) and link it to a view function
4. WE NEED A VIEW WHICH RESPOND WITH task.html
   Create a View:
   In your app's views.py file, create a view function (task_view) that will render the HTML page
5. WE NEED DYNAMIC DATA ON OUR HTML PAGE
   Configure Static Files:
   Ensure that your project's settings.py has the necessary settings for serving static files. Add the following lines to your settings.
   Run the Development Server:
   Start the Django development server by running.
   Your application should now be accessible at http://localhost:8000/url/task/ or http://127.0.0.1:8000/url/task/ , and it will display your HTML page with dynamic 
   data and the applied CSS styling.
