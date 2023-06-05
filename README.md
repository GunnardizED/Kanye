Kanye Quotes App

This is a simple Python script that displays random quotes from Kanye West using the tkinter module. The app fetches a quote from the Kanye REST API and updates the quote display when the user clicks the Kanye image button.

Prerequisites

    Python 3.x
    tkinter module
    requests module

Installation

    Make sure you have Python 3.x installed on your system.
    Install the required modules using the following command:

    pip install requests

Usage

    Save the script to a file with a .py extension (e.g., kanye_quotes.py).
    Place the background image file (background.png) and Kanye image file (kanye.png) in the same directory as the script.
    Run the script using the following command:

    python kanye_quotes.py

    The Kanye Quotes app window will appear.
    Click the Kanye image button to fetch a random quote from the API and display it on the app's interface.

Customization

You can customize the following aspects of the Kanye Quotes app:

    Background Image: Replace the background.png file with your preferred background image. Make sure to update the file path in the script accordingly.
    Kanye Image: Replace the kanye.png file with your preferred Kanye image. Make sure to update the file path in the script accordingly.
    Quote Text Styling: Modify the parameters in the canvas.create_text() line to change the font, size, and other styling options of the quote text.

API Reference

This script uses the Kanye REST API to fetch random quotes from Kanye West. Make sure you have an active internet connection for the app to function properly.
