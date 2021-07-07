# 02 Advanced CSS: Portfolio

## Description

This project requires coding a personal portfolio page from scratch that will showcase our skills to any potential employers.

Below I will show some examples of code from this project.

## Examples

CSS:
This is an example of how to use the hover attribute in order to make an element fade in and fade out

        /*Navigation bar below header where my name is, used transition attribute to fade the navigation bar in and out*/

        .navv {
            padding: 15px;
            background-color: #EDE0D4;
            transition: opacity 0.5s ease;
            opacity: 60%;
            text-align: center;
        }


        /*When the mouse moves or hovers over these elements it will fade the color back in, when the mouse moves off it'll fade back out*/

        .navv:hover,
        .about:hover,
        .work:hover {
            background-color: #EDE0D4;
            opacity: 90%;
        }
## Screenshot
![Alt text](https://i.imgur.com/pEHUFZU.png "Screenshot 1")
![Alt text](https://i.imgur.com/g1mPER2.png "Screenshot 2")
![Alt text](https://i.imgur.com/CUfawnV.png "Screenshot 3")
![Alt text](https://i.imgur.com/jqgyf00.png "Screenshot 4")

## Link to deployed application

https://kdassign.github.io/HW2Portfolio/