# general_automation
This repo is a place for me to house automation scripts.

## Purpose:
The purpose of this repo is to create a bare bones automation skeleton that can be used to quickly write a reliable automation script for the website of your choice.

## Dependencies:
- Selenium
- Python


## Helpful Notes:
### Selenium:
[Selenium](https://www.selenium.dev/documentation/en/) is a tool to automate browsers. This is accomplished via browsers starting a server and Selenium sending commands to that server, which the browser will interpret and act on ([WebDriver Protocol](https://w3c.github.io/webdriver/)).

### Selenium WebDrivers:
In order to use selenium to automate a brower, you must download the webdriver for that browser and add it to your computer's PATH. Instructions for that can be found [here](https://www.selenium.dev/documentation/en/webdriver/driver_requirements/).

### Selenium Page Object Design

Page object design is the idea of separating the low level details of how you interact with a page from the specific task of interacting with a page to accomplish a goal. More on Page Object Design can be found [here](https://selenium-python.readthedocs.io/page-objects.html).

#### For example:
In the case of Amazon, you would create a an Amazon object that has method describing actions you would like to take, such as searching for an item, logging in, etc.

If you wanted to write a script to log into Amazon, search for python books and open the top ten results in a new tab so you can review them, that would look like this:

    # TODO -- Add code snippet
    # TODO -- Add recording of code snippet?


# TODO List:
- Add instructions on how to install this repo.

- Add information on repo organization structure.
	+ Let people know where new scrips should be added.

- Add Note about how "playsound" depends on you installing "python3-gi"
