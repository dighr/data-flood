---
layout: page
title: Making Sense of WASH Information in South Sudan
description: Making Sense of WASH Information in South Sudan
sitemap:
    priority: 0.7
    lastmod: 2019-08-22
    changefreq: weekly
---
# Making Sense of WASH Information in South Sudan
## Challenge presented by REACH Initiative

### Background

At the 2018 Emergency Data Science Workshop, the REACH Initiative presented their challenge to develop a WASH Information Management (IM) Platform for South Sudan. REACH’s challenge emerged in response to difficulties faced by the WASH Cluster in South Sudan in keeping tracking of what information is available and what is up to date. WASH IM in South Sudan is atomized across many services (ReliefWeb, HumanitarianResponse.info, Google Drive, emails, etc.) so many field workers find it difficult to find the right content at the right time. Important documents are missed when making decisions, or out-of-date information is used simply because that is what is easiest to find. REACH therefore proposed to develop one universal IM platform that would cover all use cases for the South Sudan WASH Cluster. The proposed platform would be similar to ReliefWeb and HDX, but would include additional filterable fields specific to South Sudan and WASH to make data easier to find.<br>
<br>
At the workshop, REACH and UNCHR, who faced a similar WASH data-related challenge for refugee populations globally, jointly explored developing WASH data portals with a number of specialists from computer science, information management, ethics and governance, and designers and developers from the software industry. The working group consisted of representatives from the American Red Cross, George Washington University, National Research Council of Canada, Université de Sherbrooke, UNHCR, REACH, Quoin Inc., University of California Irvine, and York University. The working group brought a design thinking approach to the problem, mapping out goals and anti-goals, understanding potential users better, and figuring out what the minimum viable product (MVP) would be able to support operational decision-making.

### Progress

- Prior to the workshop, REACH contracted an external consultant to develop a content management system (CMS) to fill this gap, which underwent testing in South Sudan in early January. The field trial was not positive, as the product did not suit field conditions in South Sudan, so the REACH team went back to the drawing board and started to prototype in-house.
- During the workshop, REACH found the presentation on GO Platform by IFRC to be the most informative, as it showed how an agency could build its own ecosystem of services from scratch. REACH explored the Go Platform’s GitHub repositories to see the details of the actual implementation and started to develop its own ecosystems of platforms, using the WASH IM platform as the first test case.
- Through Spring 2019, REACH grappled with the challenge of how to use the latest technology to build the best content management system for humanitarian response? Such a CMS needs to be light, offline, easy to maintain.
- REACH first tried multiple off-the-shelf approaches to building an IM platform for low bandwidth contexts. First was with an out-of-the-box server using PHP and SQL database (Directus), which was quick to set-up, but hard to fix when something went wrong. Next was similar but with more modern frameworks including Node.js and NoSQL (Strapi); this fared better, but the framework was still in alpha and too buggy to be deployable. Next, REACH tried getting rid of servers all together and using Netlify CMS, which interacts directly with GitHub to store and modify content. Performance and maintenance were better but it was still too simple to build a complex app, and gave all-or-nothing access to different kinds of users. Off-the-shelf solutions did not seem to offer a pathway forward.
- In response, REACH next started to experiment with more fundamental building blocks. This exploration brought them to AWS's Amplify and AppSync, a serverless framework for building web apps with have fully managed services for user authentication, file storage, and database API. REACH has developed a draft version of this and is working on a production version to be live shortly.
- REACH is interested in exploring how humanitarian actors can navigate the new EU General Data Protection Regulations (GDPR) when developing new data management tools for field use. 


#### Learn More
<a href="{{ site.baseurl }}/wash_south-sudan-challenge-statement/">Full Challenge Statement</a><br>
Challenge Presentation [here](https://www.slideshare.net/dighr/challenge-4-wash-data-portal-reach)
