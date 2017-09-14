---
layout: post
title: Shopify Capital
description: Dashboard redesign for Shopify's cash advance system
img: /img/thumbnail-shopify-capital.png
---

<strong>Disclaimer:</strong> These thoughts are my own and do not necessarily represent those of Shopify. This project was taken on during the Fall of 2016.

<h2>What is Shopify Capital?</h2>

<a href="https://www.shopify.com/capital" target="_blank">Shopify Capital</a> offers funding for merchants so they can get a head start on inventory, marketing, or anything else for their business needs. These cash advances are given as a lump sum, and as the merchant makes sales, they’ll remit to Shopify a fixed percentage of their daily sales until Shopify receives the total amount of receivables purchased. This means that if the merchant doesn’t make a sale that day, they don’t have to pay Shopify. 

<h2>My Role</h2>

This project was picked up after some core problems were defined and early explorations were made. I became the lead designer on this project, with consultation from other designers and content strategists.

<h2>The Task</h2>

<ul>
<li>Define UX painpoints in the Capital dashboard with a focus on users with multiple fundings.</li>
<li>Explore potential solutions while being consistent with the Shopify brand, using existing patterns and components.</li>
</ul>

<img class="col three explore" src="{{ site.baseurl }}/img/shopify-capital-orig.png" alt="Shopify Capital original dashboard" title="Shopify Capital Dashboard"/>

This was the original Shopify Capital dashboard. There were a few problems:
<ul>
<li>Previous fundings are hidden behind a tooltip, thus making it difficult to parse multiple fundings at a glance</li>
<li>A sense of completion or accomplishment was lacking on a per funding level</li>
<li>With multiple fundings, it’s difficult for merchants to make a relationship between fundings and the returns that belong to them</li>
<li>Merchants cannot see: percentage of completion within funding, percentage of completion within all fundings</li>
<li>Fine for one funding, not great for multiple fundings. Around 80% of Capital merchants have multiple fundings</li>
</ul>

<h2>Exploration</h2>
After a some initial explorations on different approaches to take (see below), it was decided to narrow down the approach to Explore #6: buckets for each type of funding. One bucket for Active fundings, one for completed fundings, and a third for pending/future fundings.

<h3>Explore #1: Tabs</h3>

<img class="col three explore" src="{{ site.baseurl }}/img/shopify-capital-explore-1.jpg" alt="Shopify Capital original dashboard" title="Shopify Capital Dashboard"/>
<strong>Pros</strong>
<ul>
<li>Quick navigation between fundings</li>
<li>Less layers and friction to seeing data</li>
</ul>

<strong>Cons</strong>
<ul>
<li>No overview of each funding’s history</li>
<li>Not great for gaining pulse into overview of all fundings. False sense of accomplishment</li>
<li>Does not scale well beyond a certain number of fundings</li>
<li>On mobile, switching tabs, merchant could miss relationship change in top bar</li>
</ul>

<h3>Explore #2: Sheets</h3>
<img class="col three explore" src="{{ site.baseurl }}/img/shopify-capital-explore-2.jpg" alt="Shopify Capital original dashboard" title="Shopify Capital Dashboard"/>

<strong>Pros</strong>
<ul>
<li>Surfaces details without leaving page</li>
<li>Allows for cross referencing</li>
<li>Less friction in merchant workflow</li>
</ul>

<strong>Cons</strong>
<ul>
<li>Could be surprising to merchants. They’re used to other drill-down interactions in the admin</li>
<li>Doesn’t solve large index problem</li>
</ul>

<h3>Explore #3: Drill-Down</h3>
<img class="col three explore" src="{{ site.baseurl }}/img/shopify-capital-explore-3.jpg" alt="Shopify Capital original dashboard" title="Shopify Capital Dashboard"/>


<strong>Pros</strong>
<ul>
<li>Surfacing large amounts of deeper details</li>
<li>Utilizes current and existing patterns</li>
<li>Consistent interaction expectation</li>
</ul>

<strong>Cons</strong>
<ul>
<li>Cannot cross-reference data > adds friction to understanding of return and funding relationship</li>
<li>Doesn’t solve large index problem</li>
</ul>

<h3>Explore #4: Funding Dropdown</h3>
<img class="col three explore" src="{{ site.baseurl }}/img/shopify-capital-explore-4.jpg" alt="Shopify Capital original dashboard" title="Shopify Capital Dashboard"/>

<strong>Pros</strong>
<ul>
<li>Very easy implementation</li>
<li>Less jarring change for merchants from current implementation of transaction page</li>
</ul>

<strong>Cons</strong>
<ul>
<li>Not as much of a visual experience as other “bucket approaches"</li>
<li>Not great for gaining insight into an overview of all fundings. Could result in a false sense of accomplishment</li>
</ul>

<h3>Explore #5: Bucket Navigation Tabs</h3>
<img class="col three explore" src="{{ site.baseurl }}/img/shopify-capital-explore-5.jpg" alt="Shopify Capital original dashboard" title="Shopify Capital Dashboard"/>

<strong>Pros</strong>
<ul>
<li>Lets merchants stay on one page to view their fundings</li>
</ul>

<strong>Cons</strong>
<ul>
<li>Partial state layout doesn’t optimize for space</li>
</ul>


<h3>Explore #6: Buckets</h3>
<img class="col three explore" src="{{ site.baseurl }}/img/shopify-capital-explore-6.jpg" alt="Shopify Capital original dashboard" title="Shopify Capital Dashboard"/>

<strong>Pros</strong>
<ul>
<li>Approachable for merchants to understand multiple fundings</li>
<li>Presented in visual, understandable buckets</li>
<li>Individual funding progresses at a glanceable view</li>
</ul>

<strong>Cons</strong>
<ul>
<li>Partial state could potentially feel empty</li>
<li>Existing merchants may be surprised by the change of layout</li>
</ul>

<h3>Explore #7: Bucket List Timeline</h3>
<img class="col three explore" src="{{ site.baseurl }}/img/shopify-capital-explore-7.jpg" alt="Shopify Capital original dashboard" title="Shopify Capital Dashboard"/>

<strong>Pro:</strong> Works well on mobile
<br/>
<strong>Con:</strong> Could be expensive to build


<h2>The Proposed Solution</h2>
After the initial exploration, I went to higher fidelity and explored potential designs to establish layout and visual hierarchy. Throughout this process, I touched base with the PM, other designers for feedback, and content strategists to keep the copy consistent, friendly, and understandable.
<br/><br/>
Here are some snapshots of the final proposed solution (please contact me if you're interested in seeing more!):
<br/><br/>
<img class="col three" src="{{ site.baseurl }}/img/shopify-capital-1.png" alt="Shopify Capital original dashboard" title="Shopify Capital Dashboard"/>
<img class="col three" src="{{ site.baseurl }}/img/shopify-capital-2.png" alt="Shopify Capital original dashboard" title="Shopify Capital Dashboard"/>
<img class="col three" src="{{ site.baseurl }}/img/shopify-capital-3.png" alt="Shopify Capital original dashboard" title="Shopify Capital Dashboard"/>