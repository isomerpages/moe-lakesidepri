---
title: Total Defence Day
permalink: /announcements-and-latest-happenings/latest-happenings/permalink/
date: 2023-02-13
layout: post
description: ""
image: ""
---

  <style>
    html {
      box-sizing: border-box;
    }
    
    *, *:before, *:after {
      box-sizing: inherit;
    }
    
    body {
      margin: 0;
    }
    
    .preview {
      width: 100%;
    }
    
    .row {
      display: flex;
      flex-direction: row;
      justify-content: space-between;
    }
    
    .row > .col {
      padding: 0 8px;
    }
    
    .col {
      float: left;
      width: 25%;
    }
    
    .modal {
      display: none;
      position: fixed;
      z-index: 1;
      padding: 10px 62px 0px 62px;
      left: 0;
      top: 0;
      width: 100%;
      height: 100%;
      overflow: auto;
      background-color: black;
    }
    
    .modal-content {
      position: relative;
      display: flex;
      flex-direction: column;
      justify-content: center;
      margin: auto;
      padding: 0 0 0 0;
      width: 80%;
      max-width: 1200px;
    }
    
    .slide {
      display: none;
    }
    
    .image-slide {
    	width: 100%;
    }
    
    .modal-preview {
    	width: 100%;
    }
    
    .dots {
    	display: flex;
    	flex-direction: row;
    	justify-content: space-between;
    }
    
    img.preview, img.modal-preview {
      opacity: 0.6;
    }
    
    img.active,
    .preview:hover,
    .modal-preview:hover {
      opacity: 1;
    }
    
    img.hover-shadow {
      transition: 0.3s;
    }
    
    .hover-shadow:hover {
      box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    } 
    
    .close {
      color: white;
      position: absolute;
      top: 10px;
      right: 25px;
      font-size: 35px;
      font-weight: bold;
    }
    
    .close:hover,
    .close:focus {
      color: #999;
      text-decoration: none;
      cursor: pointer;
    }
    
    .previous,
    .next {
      cursor: pointer;
      position: absolute;
      top: 50%;
      width: auto;
      padding: 16px;
      margin-top: -50px;
      color: white;
      font-weight: bold;
      font-size: 20px;
      transition: 0.6s ease;
      border-radius: 0 3px 3px 0;
      user-select: none;
      -webkit-user-select: none;
    }
    
    .next {
      right: 0;
      border-radius: 3px 0 0 3px;
    }
    
    .previous:hover,
    .next:hover {
      background-color: rgba(0, 0, 0, 0.8);
    }
  </style>
  <div class="row">
    <div class="col">
       <img alt="Toy car on the road." class="hover-shadow preview" src="https://static.pexels.com/photos/385997/pexels-photo-385997.jpeg">
    </div>
    <div class="col">
       <img alt="Toy car exploring offroad." class="hover-shadow preview" src="https://static.pexels.com/photos/574521/pexels-photo-574521.jpeg">
    </div>
    <div class="col">
       <img alt="Toy car in the city" class="hover-shadow preview" src="https://static.pexels.com/photos/386009/pexels-photo-386009.jpeg">
    </div>
  </div>
  
  <div class="modal" id="Lightbox">
  
    <span class="close pointer">×</span>
    <div class="modal-content">
      <div class="slide">
        <img alt="Toy car on the road." class="image-slide" src="https://static.pexels.com/photos/385997/pexels-photo-385997.jpeg">
      </div>
      <div class="slide">
        <img alt="Toy car exploring offroad." class="image-slide" src="https://static.pexels.com/photos/574521/pexels-photo-574521.jpeg">
      </div>    
      <div class="slide">
        <img alt="Toy car in the city." class="image-slide" src="https://static.pexels.com/photos/386009/pexels-photo-386009.jpeg">
      </div>
    
      <a class="previous">❮</a>
      <a class="next">❯</a>
          
      <div class="dots">
        <div class="col">
          <img alt="Toy car on the road." class="modal-preview hover-shadow" src="https://static.pexels.com/photos/385997/pexels-photo-385997.jpeg">
        </div>
        <div class="col">
          <img alt="Toy car exploring offroad." class="modal-preview hover-shadow" src="https://static.pexels.com/photos/574521/pexels-photo-574521.jpeg">
        </div>
        <div class="col">
          <img alt="Toy car in the city" class="modal-preview hover-shadow" src="https://static.pexels.com/photos/386009/pexels-photo-386009.jpeg">
        </div>
      </div>
    </div> 
  </div>
  
  
