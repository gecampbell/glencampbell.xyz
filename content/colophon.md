+++
author = "Glen Campbell"
date = "2025-04-01T18:38:43-07:00"
draft = false
tags = ["other", "web", "technology", "hugo", "amazon", "s3", "route53", "cloudfront", "perl", "awk", "sed"]
title = "Colophon"

+++

This site is built with the [Hugo](http://gohugo.io) static site generator.
All of the content is written in 
[Markdown](http://daringfireball.net/projects/markdown/)
and it is all managed in a 
[Github repository](https://github.com/gecampbell/galliard.xyz).
(If you feel so inclined, you're welcome to add content
and submit a pull request.)

The typeface is 
[Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond).
It's available via 
[Google Fonts](https://fonts.google.com/).

The style sheet borrows from 
[Tufte CSS](https://github.com/edwardtufte/tufte-css/),
a cascading style sheet that attempts to implement some of
the ideas of Edward Tufte in 
[The Visual Display of Quantitative Information](http://www.amazon.com/The-Visual-Display-Quantitative-Information/dp/0961392142),
a profoundly important work in understanding how information is presented.
Since this site is mostly prose and not data, it does not use all
of Tufte's ideas, though I venerate them.

The static site is hosted on 
[Amazon S3](https://aws.amazon.com/s3/)
and is served via
[Amazon CloudFront](https://aws.amazon.com/cloudfront/).
All the DNS is handled by
[Amazon Route53](https://aws.amazon.com/route53/).
The script used to upload the site is stored in the `/tools`
directory of the repository.
The [podcast](/podcast.html) audio files (and some static images)
are also served via S3 and CloudFront. 

Note that 
[Perl](https://www.perl.org),
[sed](https://www.gnu.org/software/sed/manual/sed.html), and
[awk](http://www.gnu.org/software/gawk/manual/gawk.html)
were sometime used in the maintenance of the site,
but almost never these days.
