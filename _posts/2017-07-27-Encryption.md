---
layout: post
title: " encrytion test  "
date: 2017-07-31
categories: encryption images
tags: encryption 
author: Himanshu Sinha
image: /blog_image/2015_BLOGS/2/plot_2.png
---


ENCRYPTION ENCRYPTION ENCRYPTION ENCRYPTION 

<script>
function password() {
  var testV = 1;
  var pass1 = prompt('Enter Your Password', ' ');
  while (testV < 3) {
    if (!pass1)
      history.go(-1);
    if (pass1.toLowerCase() == "Guest") {
      alert('Password Correct');
      window.open("Yournextpage.html");
      break;
    }
    testV += 1;
    var pass1 =
      prompt('Access Denied - Password Incorrect, Please Try Again.', 'Password');
  }
  if (pass1.toLowerCase() != "password" & testV == 3)
    history.go(-1);
  return " ";
}
</script>

