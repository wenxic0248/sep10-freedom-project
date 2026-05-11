# Entry 6
##### 5/10/26
## Context
It's the end of the year and it was time to put our skills to the test through the whole yeasr we have learned things like html, css ,github, advance web design and bootstrap components and wire frame with all of these we had to make our freedom project topic website for my website it was cooking so i did a lot of research on it. First i made a wire frame mapping out my design on how my ending product will look like then we made a plan on what components we wanted to add or color schemes. ANd we got to coding our websites and along the way i did find a good amount of bugs if you were wondering [here is my wire frame](https://wireframe.cc/PQX5Ud) and [compared to my website](https://wenxic0248.github.io/sep10-freedom-project/)


Challenge #1
Orginally when i had made my images all the same size in my code it filled up my card's empty space but this also messed up my mobile design because when you were in mobile screen size it will just not fit intot he card and a big part of the image will be outside of the the card
```css
img{
Height:250px;
width:250px;
}
```
A simple fix to this issue was that i just changed the size for those images all into a smaller size like
```css
img{

height:200px;
width:150;

}
```
Challenge #2
When i first tried making my nav bar to bring you down to parts of my website say part B of my project or part A or even the Content part i first tried writing like content but it didn't wokr at all because it tried to bring you to a different page that was named content but i didn't have one so it will give u like a error page
```html
<div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="Context.html">Context</a>
        </li>
```
I later figured out all you ahd to do is make div classes for that part and add an # into the code like say your div class was named content you would just add #content into the href linka nd ti will bring you down

```html
<div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="#Context">Context</a>
        </li>

```
[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
