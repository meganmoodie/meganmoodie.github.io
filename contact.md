---
title: "Megan Moodie"
description: "Contact Me"
layout: default
---

## Email: <a id="email-link" href="mailto:megancmoodie@gmail.com">megancmoodie@gmail.com</a>

<script> 
  
@import "jekyll-theme-cayman"; 
  .btn {
    display: inline-block;
    margin-bottom: 1rem;
    color: rgba(255, 255, 255, 0.7);
    background-color: rgba(255, 255, 255, 0.08);
    border-color: rgba(255, 255, 255, 0.2);
    border-style: solid;
    border-width: 1px;
    border-radius: 0.3rem;
    transition: color 0.2s, background-color 0.2s, border-color 0.2s;
  
    &:hover {
      color: rgba(255, 255, 255, 0.8);
      text-decoration: none;
      background-color: rgba(255, 255, 255, 0.2);
      border-color: rgba(255, 255, 255, 0.3);
    }
  
    + .btn {
      margin-left: 1rem;
    }
  
    @include large {
      padding: 0.75rem 1rem;
    }
  
    @include medium {
      padding: 0.6rem 0.9rem;
      font-size: 0.9rem;
    }
  
    @include small {
      display: block;
      width: 100%;
      padding: 0.75rem;
      font-size: 0.9rem;
  
      + .btn {
        margin-top: 1rem;
        margin-left: 0;
      }
    }
  }
</script>

<button onclick="copyEmail()">Copy Email</button>

<script>
function copyEmail() {
  const email = "megancmoodie@gmail.com";
  navigator.clipboard.writeText(email).then(function() {
    alert('Email Copied To Clipboard');
  }, function(err) {
    console.error('Could Not Copy Email: ', err);
  });
}
</script>

-----

#### Web page created by [Toma Brasoveanu](https://meganmoodie.github.io/toma.html) using Jekyll
