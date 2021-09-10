# portfolio
![license](https://img.shields.io/badge/license-MIT-blue)

## Table of Contents 
- [Description](#description)
- [Technologies](#technologies)
- [Code](#code)
- [Usage](#usage)
- [Contribution](#contribution)
- [Author](#author)

## Description
This homework assignment was to update my portfolio website to showcase my progress. The website has the components: the Navigation bar (with Resume), the About Me section, the Work section, and the Contact Me section. Three projects/assignments are shown in the Work section. They redirect to the deployed application or the GitHub repo.

## Technologies
This website was written in HTML/CSS on Visual Studio, using Terminal to access the Github repo with git. Bootstrap was used to create cards.

## Code
Flexbox was used for the display/positioning of the content.
```html
.container {
    flex: 4;
    background-color: #fff;
    padding: 50px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    align-items: flex-start;
    margin-left: 100px;
}
```

To make the page mobile responsive, I added:
```html
@media (max-width: 600px) {
    .contact-me ul {
        font-size: small;
        display: inline-block;
    }
}
```

## Usage
![Demo Walkthrough](./assets/demo.gif)
The final website can be found here: [Website Portfolio](https://samyuhan.github.io/portfolio/)

## License
MIT License - A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.
## Contribution
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](code_of_conduct.md)
## Author
- Github: [samyuhan](https://github.com/samyuhan)
- Email: syuhan@berkeley.edu
