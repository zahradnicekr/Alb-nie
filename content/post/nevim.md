---
title:  "Welcome to Hugo!"
date:   2018-03-13
tags: 
    - hello world
    - start
    - hugo
---
You’ll find this post in your `content/post` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run command `hugo server`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `content/post` directory that follows the convention `name-of-post.md` and includes the necessary front matter. You can even create it with command `hugo new post/name-of-post.md` (you need to be at site's root folder). Take a look at the source for this post to get an idea about how it works.

When you want to publish an article, simply remove `draft: true` from it's front matter.


## What's next?

See [another post]({{< ref "another-post.md" >}}) or head back to [homepage](../../). (Check this paragraph to see the magic behind the between posts.)

<!DOCTYPE html>
<html>
<head>
  <title>Zpracovanı úkol</title>
</head>
<body>
 
 
// embed kód - video z youtube
<blockquote class="embedly-card"><h4><a href="https://www.youtube.com/watch?v=R8M1d4KhiCk">Jakub Tomala - Hromy bijú a déš prší, leje sa</a></h4><p>Verbuòk z Uherskobrodska v podání Jakuba Tomaly, Petra Vozára, Jiøího Vozára a Jakuba Jurigy.</p></blockquote>
<script async src="//cdn.embedly.com/widgets/platform.js" charset="UTF-8"></script>

// iframe kód - v rámeèku je odkaz na stránku na wikipedii


<iframe src=https://cs.wikipedia.org/wiki/Bohuslavice_(Kyjov) width="300" height="100">
</iframe>


<script type="text/javascript"><!--
document.write("Ahoj svìte!");
//--></script>

// toto je script

</body>
</html>
