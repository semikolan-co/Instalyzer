# Instalyzer
Instalyzer is an application enabling you to search through Instagram's content providing additional functionalities.

## Installation
<!-- Stting Up Local Enviroment for React Project -->
Before Any of the following steps, make sure you have installed the Nodejs and Git in your system. You can simply install Nodejs from [here](https://nodejs.org/en/) and Git from [here](https://git-scm.com/downloads)
Now you can follow the steps below to install Instalyzer.
Fork the [Github Repository](https://github.com/semikolan-co/Instalyzer) and clone it to your local machine. You can clone using a simple command like this:
```shell
git clone https://github.com/<your_username>/Instalyzer.git 
``` 

Then move to the root directory of the cloned repository. You can do this by typing the following command:
```shell
cd Instalyzer
```

Now run the following command to install the dependencies:
```shell
npm install
```
Now you can run the following command to start the server:
```shell
npm start
```
Congratulations! You have successfully installed Instalyzer. Your server is running on localhost:3000

### File Structure
Within the download you'll find the following directories and files:

```
InstaLyzer
.
├── CHANGELOG.md
├── ISSUE_TEMPLATE.md
├── README.md
├── package.json
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── index.js
    ├── variables
    │   └── charts.js
    ├── assets
    │   ├── css
    │   │   ├── blk-design-system-react.css
    │   │   ├── blk-design-system-react.css.map
    │   │   ├── blk-design-system-react.min.css
    │   │   └── nucleo-icons.css
    │   ├── demo
    │   │   └── demo.css
    │   ├── fonts
    │   │   ├── nucleo.eot
    │   │   ├── nucleo.ttf
    │   │   ├── nucleo.woff
    │   │   └── nucleo.woff2
    │   ├── img
    │   └── scss
    │       ├── blk-design-system-react
    │       │   ├── bootstrap
    │       │   │   ├── mixins
    │       │   │   └── utilities
    │       │   ├── custom
    │       │   │   ├── cards
    │       │   │   ├── mixins
    │       │   │   ├── sections
    │       │   │   ├── utilities
    │       │   │   └── vendor
    │       │   └── react
    │       │       └── react-differences.scss
    │       └── blk-design-system-react.scss
    ├── components
    │   ├── Footer
    │   │   └── Footer.js
    │   ├── Navbars
    │   │   ├── ComponentsNavbar.js
    │   │   └── ExamplesNavbar.js
    │   └── PageHeader
    │       └── PageHeader.js
    └── views
        ├── Index.js
        ├── IndexSections
        │   ├── Basics.js
        │   ├── Download.js
        │   ├── Examples.js
        │   ├── JavaScript.js
        │   ├── Navbars.js
        │   ├── Notifications.js
        │   ├── NucleoIcons.js
        │   ├── Pagination.js
        │   ├── Signup.js
        │   ├── Tabs.js
        │   └── Typography.js
        └── examples
            ├── LandingPage.js
            ├── ProfilePage.js
            └── RegisterPage.js
```


Instalyzer is built using a pre-built Template [BLK Design System](https://github.com/creativetimofficial/blk-design-system-react/) by [Creative Tim](https://github.com/creativetimofficial/)
