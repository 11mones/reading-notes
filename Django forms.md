# Django forms
### What is Django forms?


Django Forms is a component of the Django web framework that provides a high-level, Pythonic way to handle HTML forms. It simplifies
the process of building and processing forms in web applications by providing an abstraction layer that encapsulates form fields,
validation, rendering, and data processing.


Here are some key components involved in creating a form using the Django framework:


* Creating a Form Class: To define a form, you typically create a subclass of the django.forms.Form class. Within the form class, you specify the fields you want to include in the form. Each field is represented by a form field class such as CharField, EmailField, IntegerField, etc.

* Field Validation: Django form fields have built-in validation methods to ensure that the user input is valid. For example, you can specify a field as required, set minimum and maximum values, specify regular expressions for validation, and more. Django handles validation automatically and provides error messages when necessary.

* Rendering the Form: Django provides a template tag, {% form %}, to render a form in a template. This tag generates the necessary HTML for each form field, including labels, input elements, and error messages. You can customize the form rendering by manually specifying the HTML markup or by using form widgets.

* Processing Form Submission: When a user submits a form, Django handles the form data automatically. In the view function or class-based view, you can instantiate the form class and pass the request data to it. Django takes care of validating the form data, populating cleaned data, and providing error messages if validation fails.

* Displaying Form Data: After form submission, you can access the cleaned and validated form data. You can use this data to perform further processing, such as saving it to a database, sending emails, or displaying a success message to the user.

* Handling Form Errors: If the form validation fails, Django provides error messages for each field with validation errors. You can display these error messages in the template next to the respective form fields to help users correct their input.


# The purpose of Django templates


Django Templates are an integral part of web development with Django. They enable you to define the structure and layout of web pages using
HTML and provide features for rendering dynamic content. Templates promote code reusability and maintainability by allowing you to create
a base template that can be extended and overridden by child templates. Template inheritance ensures consistent design across multiple pages
while allowing customization. By separating presentation logic from business logic, Django Templates help in building robust and maintainable
web applications.






# How Django views handles HTTP requests
Django Views play a crucial role in handling HTTP requests and form the bridge between the web browser and the application's business
logic. They receive incoming requests, process them, and return appropriate responses. Views determine what should be done with a particular
URL and define the logic for rendering templates, retrieving data from models, and performing any necessary operations.


### Differences between function-based views and class-based views 


**Function-Based Views (FBVs):**


*Implemented as Python functions.*


*Simple and flat structure.*


*More flexibility.*


*Can become verbose and repetitive.*




**Class-Based Views (CBVs):**


*Implemented as Python classes.*


*Promote reusability and code organization.*


*Support mixins for modular behavior.*


*Higher complexity.*


*Improved code readability.*
