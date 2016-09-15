# contact-us
In Part III of our series on Contact Us Pages, [Solodev](https://www.solodev.com/) will provide a clean, simple design for a mobile responsive contact page. Simply place the design between your header and footer and you've got a brand new contact us page!

## Tutorial

For detailed instructions, view Solodev's [Design a Contact Us Page for your Website](https://www.solodev.com/blog/web-design/design-a-contact-us-page-for-your-website.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/f52vL14f/).

## HTML

The contact us page contains the following basic HTML markup.

```
<div id="highlighted" class="hl-basic hidden-xs">
   <div class="container-fluid">
      <div class="row">
         <div class="col-sm-9 col-sm-offset-3 col-md-9 col-md-offset-3 col-lg-10 col-lg-offset-2">
            <h1>
               Contact Us
            </h1>
         </div>
      </div>
   </div>
</div>
<div id="content" class="interior-page">
<div class="container-fluid">
<div class="row">
<!--Sidebar-->
<div class="col-sm-3 col-md-3 col-lg-2 sidebar equal-height interior-page-nav hidden-xs">
   <div class="dynamicDiv panel-group" id="dd.0.1.0">
      <div id="subMenu" class="panel panel-default">
         <ul class="panel-heading">
            <li class="subMenuHighlight panel-title">
               <a id="li_291" class="subMenuHighlight" href=""><span>Our Team</span></a>
            </li>
         </ul>
         <ul class="panel-heading">
            <li class="panel-title">
               <a class="subMenu1" href=""><span class="subMenuHighlight">Contact Us</span></a>
            </li>
         </ul>
         <ul class="panel-heading">
            <li class="panel-title">
               <a class="subMenu1" href=""><span>FAQ</span></a>
            </li>
         </ul>
      </div>
      <div>
         <a style="padding: 5% 0px;" href="" class="btn btn-primary btn-block" role="button">LEARN MORE</a> 
      </div>
   </div>
</div>

<!--Content-->
<div class="col-sm-9 col-md-9 col-lg-10 content equal-height">
  <div class="content-area-right">
   <div class="content-crumb-div">
      <a href="">Home</a> | <a href="">About Us</a> | Contact Us
   </div>
    <p>Please fill out the form below and we will contact you as soon as possible.</p>
      <div class="row">
         <div class="col-md-6 forgot-form">
            <label class="label-default" for="un">First Name</label> 
               <input id="" name="" class="form-control" type="text">
         </div>
         <div class="col-md-6 forgot-form">
            <label class="label-default" for="un">Last Name</label>
               <input id="" name="" class="form-control" type="text">
         </div>
      </div>
      <div class="row">
         <div class="col-md-6 forgot-form">
            <label class="label-default" for="un">Email Address</label> 
               <input id="" name="" class="form-control" type="text">
         </div>
         <div class="col-md-6 forgot-form">
            <label class="label-default" for="un">Phone Number</label>
               <input id="" name="" class="form-control" type="text">
         </div>
      </div>
      <div class="row">
         <div class="col-md-12">
            <label class="label-default" for="un">Comment / Question</label>
            <textarea class="form-control" type="text"></textarea>
         </div>
      </div>
      <br>
         <a id="" class="btn btn-primary" role="button">Submit</a>
      </div>
   </div>
</div>
```
## CSS

All necessary CSS is included in contact-us.css

## External Includes

This tutorial includes the following third party resources.

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="contact-us.css">
```
