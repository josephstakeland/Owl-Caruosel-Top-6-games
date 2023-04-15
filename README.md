<table>
<tr>
        <td align="center">
                <a></a>
        </td>
        <td align="center">
                <a><img src="https://getbootstrap.com/docs/5.0/assets/brand/bootstrap-logo.svg" width=200></a>
        </td>
        <td align="center">
                <a></a>
        </td>
        <td align="center">
            <a><img src="https://owlcarousel2.github.io/OwlCarousel2/assets/img/owl-logo.png" width=130></a>
        </td>
    </tr>
</table>

# Introduction

This project aims to create a carousel using owl carousel and bootstrap 5,taking into account my 6 expected games.

## Owl-Caruosel

OWL Carousel is another plugin to add sliders or carousels to your Web pages. It is prepared for all devices, it can be easily designed to your liking and it has an infinite number of options like other plugins.


The features that most attract our attention are its easy implementation and the way in which it adapts to different devices.

## How to use

To use this plugin we just have to add the necessary styles and scripts + the call to the plugin in the header or ```<head>```l of our page:
```html
<!--Owl Carousel Min.css-->

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css" integrity="sha512-tS3S5qG0BlhnQROyJXvNjeEM4UpMXHrQfTGmbQ1gKmelCxlSEBUaxhRBj/EFTzpbP4RVSrpEikbmdJobCvhE3g==" crossorigin="anonymous" referrerpolicy="no-referrer" />

<!--Owl Carousel Theme Min.css-->

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.theme.default.min.css" integrity="sha512-sMXtMNL1zRzolHYKEujM2AqCLUR9F2C4/05cdbxjjLSRvMQIciEPCQZo++nk7go3BtSuK9kfa/s+a4f4i5pLkw==" crossorigin="anonymous" referrerpolicy="no-referrer" />

```

Also keep in mind that the plugin works with jquery 1.7 or higher.

```html
<!-- Jquery cdn -->

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.4/jquery.min.js" integrity="sha512-pumBsjNRGGqkPzKHndZMaAG+bir374sORyzM3uulLV14lN5LyykqNk8eEeUlUkB3U0M4FApyaHraT65ihJhDpQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
```

In the ```<body>``` of your page where you want to add the carousel you must put the following structure in HTML:

```html
<div class="owl-carousel owl-theme">
    <div class="item"><h4>1</h4></div>
    <div class="item"><h4>2</h4></div>
    <div class="item"><h4>3</h4></div>
    <div class="item"><h4>4</h4></div>
</div>
```

Finally to initialize the carousel we must add the following ```<scrip>```


```html
<!-- Init Owl Carousel -->

<script> 
$('.owl-carousel').owlCarousel({
loop:true,
margin:10,
nav:true,
responsive:{
    0:{
        items:1
    },
    600:{
        items:2
    },
    1000:{
        items:3
    }
     }
})

</script>
```
# Credits and refereces

This repository was created by [josephstakeland](https://github.com/josephstakeland).

- Links:
	- [owlcarousel](https://owlcarousel2.github.io/OwlCarousel2/index.html)
	- [Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
	- [josephstakeland](https://www.youtube.com/c/CodeNoSchool)
	- [Linkedin](https://www.linkedin.com/in/josephvazquezwebdesing/)