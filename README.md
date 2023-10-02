# CodeClauseInternship_Url-Shortener
This Python script shortens a given URL using the pyshorteners library, which provides an interface to various URL shortening services.

Here's an explanation of the code:

1- Import the pyshorteners module:

🌟 pyshorteners is a Python library that allows you to interact with various URL shortening services.
2- Define the shorten_url(url) function:

🌟 This function takes a URL as input.

🌟 It creates an instance of the Shortener class from pyshorteners.

🌟 It uses the tinyurl service to shorten the provided URL.

🌟 The shortened URL is returned.

3- Define the main() function:

🌟 This function is the entry point of the program.

🌟 It prompts the user to enter a URL they want to shorten.

🌟 It then calls the shorten_url() function with the user-provided URL.

4-In the main() function:

🌟 The user is prompted to enter a URL.

*The shorten_url() function is called with the entered URL, and the shortened URL is stored.

5- Finally, the shortened URL is printed to the console.

6- The name block ensures that the main() function is called when the script is run directly.

Overall, this script provides a simple command-line interface for shortening URLs using the pyshorteners library. Users can input a URL, and the script will return the shortened version using the TinyURL service.
