---
title: "Megan Moodie"
description: "Contact Me"
layout: default
---

## Email: <a id="email-link" href="mailto:megancmoodie@gmail.com">megancmoodie@gmail.com</a>

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
