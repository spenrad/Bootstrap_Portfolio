Bootstrap Portfolio
======
## Introduction
The aim of this project is to create a responsive portfolio using Bootstrap and it's built in stylings. Learning to use Bootstrap can save one a lot of time as they have great pre-built components and styling compatibility. Although a little bit of CSS can not be avoided utilizing Bootstrap, one can keep their CSS styling to a minimum.

----

## What do you need?
All you have to do is include a link in your `<head>` to Bootstraps CDN (Content Delivery Network.) It can be found on their website, or right here!
```
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
```
Once you've entered this all you need to do is paste the javascript they provide someonwhere in your document as well.
```
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW" crossorigin="anonymous"></script>
```
Now you're ready to start using Bootstrap!

----

## What's used in this project?
This project includes Bootstrap components that were formatted in mere seconds that would otherwise have taken much longer to program and stlye by one's self.

In the next images you will see a Navigation Bar and a grid of images that were formatted using solely Bootstrap.

![Demo](assets/992.jpg)

This may not look like much, but once the page resizes Bootstrap's power is realized.

![Demo](assets/lt768.jpg)

The Navigation Bar collapses and the grid of images reorganizes itself in a very responsive manner, and this is all built in to Bootstrap, no other styling or formatting was necesary. Even at smaller dimensions, the webpage remains responsive in different ways thanks to Bootstrap.

![Demo](assets/ls576.jpg)

It is even easy to customize one's website for mobile devices.

![Demo](assets/400px.jpg)

The code here is very simple
```
<div class="container bg-white col-md-7 col-sm-7 col-11">
      <h1>Portfolio</h1>
          <hr>
      <div class="row">
            <div class="col-md-6"><img src="https://via.placeholder.com/350" class="img-fluid" alt="placeholder" />
            </div>
            <div class="col-md-6"><img src="https://via.placeholder.com/350" class="img-fluid" alt="placeholder" />
            </div>
      </div>
    ...
</div>
```
This alone will give the responsiveness that is seen in the webpage. As for the Navigation Bar all that was needed was to copy and paste from their website, the responsiveness was built in.

----

## Built Using
* HTML
* Bootstrap
* CSS
* Google Fonts
* Git
* GitHub
* subtlepatterns.com

----

## Acknowledgements
Thank you to [subltpatterns.com](https://www.toptal.com/designers/subtlepatterns/swirl-2/) for providing the background image used on the page. Its a great website for exactly what it says, subtle patterns.

## Author
Spencer Christy<br>
[GitHub](https://github.com/spenrad)<br>
[LinkedIn](https://www.linkedin.com/in/spencer-christy-543b84b3/)<br>