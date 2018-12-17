---
title: Forget to Update Your Footer Year? Here's Some Code for That
date: 2018-07-02T20:21:43.544Z
description: >-
  Recently on the site I noticed our footer wasn't updated with the current year
  (2018).
---
From personal experience, if I land on a page with an outdated year, there's a good chance that I feel it might be outdated. And of course I don't want to feel outdated! It's a simple fix that should be implemented. Here's a simple script to update your footer with some javascript code that will make your footer dynamic instead of static!

    <script type="text/javascript">
      document.write(new Date().getFullYear());
    </script>

This is a really simple script that I picked up from [updateyourfooter.com](http://updateyourfooter.com/) If you'd like something a bit more sophisticated, use this:

    &copy; 2010
    <script type="text/javascript"> 
    new Date().getFullYear()>2010&&document.write("-"+new Date().getFullYear());
    </script>, Company.

As stated on their site, "_Friends Don't Let Friends Look Dead On The Internet_". Hope this helps you!
