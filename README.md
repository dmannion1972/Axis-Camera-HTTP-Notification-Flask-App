# Axis-Camera-HTTP-Notification-Flask-App

Using an Axis Camera you can send http notifications to this application.  This Python code sets up a Flask web application that listens for incoming HTTP GET and POST requests on the '/receive_notification' route. When a request is received, it attempts to extract text data from the request, whether it's provided as query parameters in a GET request or in the request body of a POST request. The code handles different types of incoming requests, such as GET and POST.
