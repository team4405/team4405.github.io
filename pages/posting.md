---
layout: page
title: "Post to the Blog"
subheadline: ""
show_meta: false
teaser: ''
permalink: "/posting/"
---



##Method 1: Regular Poster

If you think you will be a regular poster here, then please follow this method as you will be able to do all of this yourself and readily access your previous posts and make new ones. 

In order to post to the blog, you first need to have a github account and be added as a member of the team4405 organization by one of the administrators. Once you are added, go to [prose.io](http://prose.io/) and click "Authorize on Github." This may ask you to log in to your github account, but once you are in, you will then see a list of all you github repositories. Click on "team4405.github.io" and there you will see a list of all the posts on the blog. You can click the "New File" button to create a new post. 

When you are finished writing your post, on the right hand side of the page, click "save", and then click on "Meta Data." Here you can enter some detail about your post such as who wrote it and a Title and Subtitle. If you are are ready for the world to see it, check the box that says "Published" and your post will be put on the website in a few moments. 

##Method 2: Feature Article

If you are not a regular poster to the blog or are writing a feature article, please use this method.

To get your post to the blog, simply fill out the form below and we will post it for you. If the form doesn't work, please just send all of the information that the form asks you in an email to [software@team4405.com](mailto:software@team4405.com) and we will get back with you. 

<script src="http://cdn.ckeditor.com/4.5.1/standard/ckeditor.js"></script>

<form class="form-horizontal" action="http://formspree.io/software@team4405.com" method="POST">
<fieldset>

<!-- Form Name -->
<legend>Submit a Post</legend>

<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="title">Title</label>  
  <div class="col-md-4">
  <input id="title" name="title" type="text" placeholder="Post Title" class="form-control input-md" required="">
    
  </div>
</div>

<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="teaser">Teaser</label>  
  <div class="col-md-6">
  <input id="teaser" name="teaser" type="text" placeholder="Short Intro to your Post" class="form-control input-md">
    
  </div>
</div>

<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="subheadline">Subheadline</label>  
  <div class="col-md-4">
  <input id="subheadline" name="subheadline" type="text" placeholder="Subtitle for you Post" class="form-control input-md">
    
  </div>
</div>

<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="author">Your Name</label>  
  <div class="col-md-4">
  <input id="author" name="author" type="text" placeholder="First Name" class="form-control input-md">
    
  </div>
</div>

<!-- Select Basic -->
<div class="form-group">
  <label class="col-md-4 control-label" for="catagories">Slelct a Category</label>
  <div class="col-md-4">
    <select id="catagories" name="catagories" class="form-control">
      <option value="championship">Championship</option>
      <option value="event">Event</option>
      <option value="announcement">Announcement</option>
      <option value="technical">Technical</option>
    </select>
  </div>
</div>

<!-- Select Multiple -->
<div class="form-group">
  <label class="col-md-4 control-label" for="tags">Choose your Tags</label>
  <div class="col-md-4">
    <select id="tags" name="tags" class="form-control" multiple="multiple">
      <option value="announcement">Announcement</option>
      <option value="district">District</option>
      <option value="championship">Championship</option>
      <option value="mechanical">Mechanical</option>
      <option value="electrical">Electrical</option>
      <option value="software">Software</option>
    </select>
  </div>
</div>

<!-- Textarea -->
<div class="form-group">
  <label class="col-md-4 control-label" for="post">Blog Post</label>
  <div class="col-md-4">                     
    <textarea class="form-control" name="post" id="post" rows="10" cols="80">post text here...</textarea>
  </div>
</div>

<!-- Multiple Checkboxes (inline) -->
<div class="form-group">
  <label class="col-md-4 control-label" for="header-image">Do you want a header image?</label>
  <div class="col-md-4">
    <label class="checkbox-inline" for="header-image-0">
      <input type="checkbox" name="header-image" id="header-image-0" value="yes">
      Yes
    </label>
  </div>
</div>

<!-- File Button --> 
<div class="form-group">
  <label class="col-md-4 control-label" for="image">Header Image Upload</label>
  <div class="col-md-4">
    <input id="image" name="image" class="input-file" type="file">
  </div>
</div>

<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="image-caption">Header Image Caption</label>  
  <div class="col-md-4">
  <input id="image-caption" name="image-caption" type="text" placeholder="caption" class="form-control input-md">
    
  </div>
</div>

<!-- Text input-->
<div class="form-group">
  <label class="col-md-4 control-label" for="caption-link">Caption URL</label>  
  <div class="col-md-4">
  <input id="caption-link" name="caption-link" type="text" placeholder="http://" class="form-control input-md">
    
  </div>
</div>

<!-- Button -->
<div class="form-group">
  <label class="col-md-4 control-label" for=""></label>
  <div class="col-md-4">
    <button id="" name="" class="btn btn-success">Submit</button>
  </div>
</div>

</fieldset>
<input type="hidden" name="_next" value="#" />
<input type="hidden" name="_subject" value="New Blog Post from Team4405.com!" />
</form>
