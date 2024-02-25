## Kanye West Quote Machine - A Python Tkinter Application

This project is a simple Python application that uses Tkinter to display random Kanye West quotes fetched from an API.

### Features:

* Displays a randomly chosen Kanye West quote.
* Refreshes the quote with a button click.
* Uses a custom background image and Kanye button for a stylish look.
* Checks quote length to ensure a good fit on the display.

### Prerequisites:

* Python 3.x
* `tkinter` module (usually included with Python)
* `requests` module (install with `pip install requests`)
* `background.png` and `kanye.png` images (place them in the same directory as the script)

### Running the application:

1. Save the code as `kanye_quotes.py`.
2. Open a terminal in the same directory.
3. Run the script with `python kanye_quotes.py`.

### How it works:

* The `get_quote` function fetches a random quote from the Kanye West API.
* It checks the quote length and recursively calls itself if the quote is too long.
* The retrieved quote is then displayed on the Tkinter canvas.
* Clicking the Kanye button triggers the `get_quote` function again, refreshing the quote.

### Contributing:

Feel free to fork this repository and make your own modifications. Pull requests are welcome!

### License:

MIT License (see LICENSE file for details).

### Author:

Nikhil Telase

**Additional notes:**

* You can customize the code further by adding features like saving quotes, displaying different types of quotes, or changing the appearance of the GUI.
* Consider including a link to the Kanye West API documentation in the README for reference.

I hope this README file is helpful and informative!
