# BBB-Voter
Automatic voter for Big Brother Brasil.

# Getting Started

## Requirements
* Python
* Firefox

## Usage
* Set the `config.json` file and run `py voter.py`.

### Configuration:
* pollURL = url where the poll is located
* targetPosition = the order of the target. For example, if one is the 2nd on the list, this attribute should be 2.
* credentials = The Globo credentials to login.
* webDriverPath = the path to the Firefox webdriver. If you want to use another browser, change line 41.

### HELP LINKS:
https://medium.com/ananoterminal/ambientar-selenium-no-windows-3b880fa0e827
