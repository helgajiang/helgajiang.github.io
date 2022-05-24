---
layout: post
title: Facebook / Advertiser Recommendations Framework
description: Product Design, Design Systems, UI/UX
img: /img/thumbnail-fb-framework.png
---

<strong>Disclaimer:</strong> These thoughts are my own and do not necessarily represent those of Facebook (Meta).

During my time at Facebook (now known as Meta), I had the opportunity to work alongside a stellar team of product designers, content designers, research, and with the support of research, product management, and org directors, to build a system for our recommendation products. This design-led effort materialized into a set of guidelines, UI elements, customized components, and a step-by-step framework of building a recommendation. We built an internal microsite and accompanying internal notes as living documentation for future designers.

<h3>The Problem Space</h3>

Design Consistency
Patterns, UI components, and resolution flows for each mid-flight recommendation are inconsistent and not in accordance with Ads Manager Design Principles. Design Efficiency
Creating new inventory for recommendations requires heavy consultation from Ads Manager + engineering and design overhead.
This is what the feature originally looked like:

<img class="col three explore" src="{{ site.baseurl }}/img/facebook/facebook-intablecard.png" alt="Facebook Recommendations Card" title="Facebook Recommendations Card"/>

The functionality is simple; all the user can really do is add some text to their Twitter or Facebook post. With Facebook in particular, the campaign URL (this is the automatic link that MailChimp sets up where the email lives on the web) is automatically attached to the post, with no customization available for the user. 

My task was to not only redesign this feature so it's visually consistent with the new overarching redesign, but also to:
<ul>
<li>Give users the ability to add photos to their posts</li>
<li>Allow users to have a customized link or remove it altogether</li>
</ul>

<h3>Exploration</h3>

With the above goals outlined, there are a few questions that come to mind:
<ul>
<li>How can we make the experience as seamless as possible? Our users already have so much on their plate -- how can we make the process easy and efficient for them?</li>
<li>The campaign URL can be helpful to include for many of our users. How can we give users the option to remove it, while still suggesting its importance?</li>
<li>How can we achieve this without making such a huge change that users overlook new functionalities -- specifically the new treatment of the campaign URL attachment?</li>
</ul>

The exploration stage of the design process involved working with user researchers, using qualitative and quantitative data to inform design decisions (including how many Facebook pages a typical MailChimp user connects to their account, how often they post, etc.), keeping communication open with the Product Manager to make sure our product goals are in mind, and of course presenting my work in weekly design reviews to receive feedback regularly from the product design team. During this process, I also kept my cross-functional team in the loop of any updates.

<h3>The Solution</h3>

After multiple iterations, we came to a solution which was fully prototyped, user tested, and submitted to engineering. Unfortunately, the final design is not yet public, but I would love to chat about it privately. <a href="mailto:jianghelga@gmail.com">Contact me</a> if you'd like to know more!