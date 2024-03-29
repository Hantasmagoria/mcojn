# MCO Jelly Noodles
>MCO Jelly Noodles is a script to deal with the issue of inefficiency in the presentation of the booking table data for our facility managers working with the MCOnline Facility booking system.

## Table of Contents
- [Current Version](#current-version)
- [Installation](#installation)
  - [Command Menu](#command-menu)
- [Installation(Alternative)](#alternative-installation)
- [Usage](#usage)
  - [Usage(Alternative)](#alternative-usage)
  - [Demonstration](#demonstration)
- [Roadmap](#roadmap)
- [Contributing](#contributing)


## Current version: 
  [3.0.7]
##  Installation
<details><summary>Disclaimer</summary><p>As of now, the only 'permanent' way to install the script is to save the script directly into the browser.
Currently the script can only be 'installed' in chrome(as far as we know), without implementing any third-party software or browser extensions. Testing has not been done on any other browsers.</p></details>

<details><summary>Possible future plans</summary><p>
we might expand the project into a userscript, in which case this section of the documentation will be updated. For now the only way to 'install' this script is via chrome's snippet devtool. running the script in any browser's console works fine(except IE9 and below). Saving the script as a bookmark also works.
</p></details>


### Command menu

In chrome, open up the [command menu.](https://developers.google.com/web/tools/chrome-devtools/command-menu/)

Type in `Snippet` and click the first option.

Paste in the [source code](#current-version) for the script.

Run the script using Ctrl + Enter, or rightclick and run.

## Alternative Installation
Alternatively, copy the code from index.js and save it as the URL of a bookmark on your browser. Anytime you need to use it just run.

## Usage

To use the script, the snippet has to be run.
>Ctrl + shift + I  -->  Ctrl + shift + P  --> backspace, type: "!"  -->  press enter.

### Alternative Usage

Run the bookmark that contains the script code.

### Demonstration

Upon loading the script, two buttons will appear above the calendar. 

<img src="demo/jifwan 1.gif" alt="figure 1">

| Button | Description |
| --- | ---- |
| Pick a Date | The First button, labelled "Pick a Date", has to be used first, to initialize the date used in the script. The "Bookings" button will not work otherwise. Upon clicking the button, an alert window will pop up on the page, asking for a date to be typed into the input box. Any date can be given, however only the date that is within the week that is shown in the calendar will be taken for the "Bookings" buton to work. |
| Bookings | The Second button, labelled "Bookings", can be used at any point in time as long as the date is initialized using the "Pick a Date" button as mentioned above. The "Bookings" button, upon being clicked, will replace the entire calendar with the information of all the bookings on the date specified. |

<img src="demo/jifwan 2.gif" alt="figure 2">

## Roadmap
Future developments will still be continued unless otherwise specified.

>Planned features:
```bash
-Make the design prettier?
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


[3.0.7]: index.js

