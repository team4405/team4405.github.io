---
layout: page
title: "Post to the Blog"
subheadline: ""
show_meta: false
teaser: ''
permalink: "/posting/"
---

<script src="http://cdn.ckeditor.com/4.5.1/standard/ckeditor.js"></script>

<form class="form-horizontal" action="http://formspree.io/gmatson@live.com" method="POST">
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
</form>
<script>
	CKEDITOR.replace( 'post' );
</script>
