# portfolio
This homework assignment was to build a portfolio website to showcase the developer's work in order to assess if they satisfy the requirements for an open position. The website has 4 components: the About Me section, the Work section, the Contact Me section, and the Resume section. 

## Technologies Used
This website was written in HTML/CSS on Visual Studio, using Terminal to access the Github repo with git.

## Essential Code
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

To change the image background when hovering over it, I added:
```html
.container img:hover {
    background-color: grey;
    opacity: 0.7
}
```

## Application Functioning
The final website can be found here: [Website Portfolio](https://samyuhan.github.io/portfolio/)