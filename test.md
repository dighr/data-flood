---
layout: page
title: Testing About Page Layout
description: This is a test of the page layout.
---

<!-- Image Linked-->
<<h1>{{ page.title }}</h1>
<a class="image main"><img src="{{ site.baseurl }}/images/picture1.jpg" alt="About" /></a>

<!-- Image Left v1-->

<span class="image left"><img src="{{ site.baseurl }}/images/picture1.jpg" alt="" /></span>
1st Way to image left - An invite-only international workshop hosted by the **Dahdaleh Institute for Global Health Research** (DIGHR) and the **Lassonde School of Engineering** (LSE) at York University that brings together leading humanitarian agencies, data scientists, and developers to collaborate on urgent data-related challenges in humanitarian response.

<!-- Image Left v2-->
<p style="clear: both"><span class="image left"><img src="{{ site.baseurl }}/images/picture1.jpg" alt="" /></span>
    2nd Way to image left- An invite-only international workshop hosted by the **Dahdaleh Institute for Global Health Research** (DIGHR) and the **Lassonde School of Engineering** (LSE) at York University that brings together leading humanitarian agencies, data scientists, and developers to collaborate on urgent data-related challenges in humanitarian response.</p>

<!-- Image Fit-->
<span class="image fit"><img src="{{ site.baseurl }}/images/pic01.jpg" alt="" /></span>


<!--
<header class="major">
									<h2>About the Event</h2>
								</header>
								<a class="image main"><img src="{{ "{{ site.baseurl }}/images/picture1.jpg"  | absolute_url }}" alt="About" /></a>
                                <p>An invite-only international workshop hosted by the <b>Dahdaleh Institute for Global Health Research</b> (DIGHR) and the <b>Lassonde School of Engineering</b> (LSE) at York University that brings together leading humanitarian agencies, data scientists, and developers to collaborate on urgent data-related challenges in humanitarian response.</p>
-->