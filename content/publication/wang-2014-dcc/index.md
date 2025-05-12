---
title: Defending Continuous Collision Detection Against Errors
authors:
- admin
date: '2014-07-01'
publishDate: '2024-03-03T02:42:26.871612Z'
publication_types:
- article-journal
publication: '*ACM Trans. Graph. (SIGGRAPH), 33*(4)'

abstract: Numerical errors and rounding errors in continuous collision detection (CCD)
  can easily cause collision detection failures if they are not handled properly.
  A simple and effective approach is to use error tolerances, as shown in many existing
  CCD systems. Unfortunately, finding the optimal tolerance values is a difficult
  problem for users. Larger tolerance values will introduce false positive artifacts,
  while smaller tolerance values may cause collisions to be undetected. The biggest
  issue here is that we do not know whether or when CCD will fail, even though failures
  are extremely rare. In this paper, we demonstrate a set of simple modifications
  to make a basic CCD implementation failure-proof. Using error analysis, we prove
  the safety of this method and we formulate suggested tolerance values to reduce
  false positives. The resulting algorithms are safe, automatic, efficient, and easy
  to implement.
summary: 'We demonstrate a set of simple modifications
  to make a basic CCD implementation failure-proof. Using error analysis, we prove
  the safety of this method and we formulate tolerance values to reduce
  false positives.'
tags:
- continuous collision detection
- floating-point arithmetic
- numerical error
- quadratic and cubic solver
- rounding error
links:
url_video: https://drive.google.com/file/d/1_UA9dER8zFA8hTMF4s0AeLZxqy705TSD/view
url_code: publication/wang-2014-dcc/Wang-2014-DCC.zip
url_source: publication/wang-2014-dcc/Wang-2014-DCC_supp.pdf
---

<p align="center">
<iframe width="100%" height="360" src="https://www.youtube.com/embed/Mg-peZuvSeM?si=fGapWfyP_30ztu0t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>
<p align="center">
<iframe width="100%" height="360" src="//player.bilibili.com/player.html?aid=467841829&bvid=BV1g5411D7Sm&cid=563637193&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
</p>
