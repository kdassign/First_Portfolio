# 02 Advanced CSS: Portfolio

## Description

This project requires coding a personal portfolio page from scratch that will showcase our skills to any potential employers.

Below I will show some CSS and HTML examples of code from this project.

## Instructions


## Examples
HTML:

This section displayed an image of me, resized.
        section class="me"
             <!-- Image of me linked below with width and height changed to fit the structure of the page-->
            <img src="https://i.imgur.com/aAGJtSS.png" alt="Picture of me " width="300px" height="450px">
        /section

This section was for deploying the application through images in "My Work" 
        section class="work"
                    <div id="my-work">
                        <h2>My Work</h2>
                        <section class="card1">
                            <!-- Link tag with image tag inside so that when the image is clicked on it takes the user to hyperlink -->
                            <a href="https://kdassign.github.io/prework-about-me/"><img
                                    src="https://cdn.pixabay.com/photo/2016/06/12/19/22/white-1452850_960_720.jpg" alt="flowers"
                                    width=300px height=300px></a>
                            <h3>Pre-work: About Me</h3>
                        </section>
                        <section class="card2">
                            <a href="https://kdassign.github.io/HW1/"><img
                                    src="https://static8.depositphotos.com/1363517/842/i/600/depositphotos_8422119-stock-photo-lower-manhattan.jpg"
                                    alt="city" width=150px height=150px></a>
                            <h3>HW1: Refactoring code</h3>
                        </section>
                        <section class="card3">
                            <a href="https://kdassign.github.io/first-day-repo/"><img
                                    src="https://images.unsplash.com/photo-1581116972164-b89ed0cdf64f?ixid=MnwxMjA3fDB8MHxzZWFyY2h8NXx8b2NlYW4lMjBzdW5zZXR8ZW58MHx8MHx8&ixlib=rb-1.2.1&w=1000&q=80"
                                    alt="ocean" width=150px height=150px></a>
                            <h3>First Day Repo</h3>
                    </div>
            /section

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