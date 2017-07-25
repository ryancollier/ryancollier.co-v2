---
layout: page
title: Socrata for Public Finance
permalink: /work/finance/
---


<p class="lead">
Reimagined, designed, and shipped the second and third major releases of Socrata for Public Finance, a suite of consumption-focused web apps that included <i>Open Budget</i>, <i>Open Expenditures</i>, and a new addition, <i>Open Payroll</i>. The product saw 10x growth in revenue the year after release.
</p>

## My Role
I was the primary designer working on Socrata for Finance. The early version of the product suite was handed to me from other members of the Socrata design team. I was paired with product manager Michael Lu to level up the product and business. I drive the design from research and discovery to prototyping, interface design, implementation, shipping, and ongoing iteration. At later stages of the product lifecycle, and as our pace increased, I pair designed with [another Socrata designer](http://www.karinhellman.com). Our team also made huge strides working alongside a fantastic group of engineers that could iterate quickly and took _bias for action_ to new heights.

## Problem
Socrata had discovered that a subject-area specific offering in government finance had the potential to be a huge success. Cities, states, and counties were looking for an out-of-the-box solution to citizen-facing financial information sharing.

The first generation of apps needed to be re-imagined for scale and repeatability. They were overly specific to the unique needs and desires of early design partners. For example, the apps were dogged by a rigid data schema, inflexible interaction patterns, and a limited design language. A key component of the user experience challenge was at once arriving at a product that was simple enough for a finance novice, yet desirable for users and buyers within the government who had deep understanding of fiscal policy and planning.

<div class="artifact-wrapper">
  <div class="image-full">
    <img src="/work/images-finance/budget-v1.png" alt="Version 1" class="img-responsive">
    <figcaption>
      <span class="title">Open Budget version 1. </span><span class="caption-body">Front page of the first version of the Open Budget application. The app included a lot of design partner-specific elements and the visuals left something to be desired.</span>
      </figcaption>
    </div>
  </div>


## Process
Understanding the problem and solution space started by taking a good look at the first generation Open Budget product and its short list of customers. I then drove the effort to develop a new, deeper understanding of user scenarios through light weight-ethnographic research, listening sessions, and user testing of the first version of the product.

### Research
We set out to answer the question of how city, county, and state government officials and finance experts educate and communicate financial information to constituents. I developed a set of question prompts and the product manager and I spent time in the field talking with customers about the problem space.

<div class="artifact-wrapper">
  <div class="image-left">
    <img src="/work/images-finance/finance-synthesis.jpg" alt="affinity diagram" class="img-responsive">
  </div>
  <div class="caption-right">
    <figcaption>
      <span class="title">Affinity diagram. </span><span class="caption-body">We synthesized the design research by pulling out verb-noun pairs, as well as interesting and surprising quotes and passages from interview transcripts and notes.</span>
      </figcaption>
    </div>
  </div>

The assumption was that the product solved a problem of fiscal transparency. While this turned out to be true on the surface, digging deeper we came to learn that there was a greater desire to educate and inform constituents about the budgeting process and to contextualize through narrative. Government finance experts know that finance is a complicated topic, and transparency in data could not exist without context.

<div class="artifact-wrapper">
  <div class="image-left">
    <img src="/work/images-finance/top-line.jpg" alt="research summary document" class="img-responsive">
  </div>
  <div class="caption-right">
    <figcaption>
      <span class="title">Top-line summary.   </span><span class="caption-body">I liked to share research findings early and often. After conducting a few interviews, I summarized our findings and included some key quotes from customers to share with the larger team.</span>
      </figcaption>
    </div>
  </div>

I also spent a good deal of time looking at competitive and analog products in the market. Governments had developed a host of home-grown solutions, used enterprise-class products; some spent millions in tax-dollars each year to fund and run what amounted to data-dense, yet information sparse websites. This provided a lot of insight about our customer’s intent as well as some good inspiration for where we could take the product surface itself.

One important discovery was that governments created elaborate infographics and newsletters to share financial information with their citizens. One large city even configured the first version of the Open Budget application to include such an infographic. The insight was that governments used their “budget” to serve information-sharing and education scenarios, while spending and checkbook-level detail—our expenditures and payroll offerings—served reporting and compliance scenarios.  

Another important insight was that while Socrata thought in terms of datasets—budget dataset, spending dataset, and so on—citizens and government workers saw these as interconnected. The product needed to divorce its technical, data-centered architecture to better support users of the end product.

Finally, there were a handful of basic usability and information design problems that I discovered through user observation and analysis of the existing products.  

### Prototyping, Design, and Testing
Orienting around our insights from research, I began design explorations with a focus on introducing narrative content into the experience. I explored ideas through sketched concepts and low fidelity wire frames.

<div class="artifact-wrapper">
  <div class="image-full">
    <img src="/work/images-finance/budget-sketch.jpg" alt="Budget Sketch" class="img-responsive">
    <figcaption>
      <span class="title">Sketch. </span><span class="caption-body">I explored a lot of concepts through sketching. Eventually, we arrived at a primary flow that employed a visualization as the primary means for navigation.</span>
      </figcaption>
    </div>
  </div>

  <div class="artifact-wrapper">
    <div class="image-full">
      <img src="/work/images-finance/budget-wireframe.png" alt="Budget Sketch" class="img-responsive">
      <figcaption>
        <span class="title">Wireframe. </span><span class="caption-body">As I iterated, I slowly increased and aligned the fidelity to the kind of input and feedback we were looking for at that stage of the project. This concept was largely about learning out how much we could change in the existing app without alienating our existing customers and the model they were already using.</span>
        </figcaption>
      </div>
    </div>

These early sketches helped me discover constraints around the data as well as the business need to make app configuration self-service for our customers.  Because the product was so data-rich, I also spent a good deal of time exploring financial data in Excel. There’s nothing quite like using real-data to examine and find the edges of an information design. Those explorations helped me arrive at many of the information visualizations that ended up in the apps.

<div class="artifact-wrapper">
  <div class="image-full">
    <img src="/work/images-finance/payroll-viz.png" alt="Payroll visualization mockup" class="img-responsive border">
    <figcaption>
      <span class="title">Visualization design. </span><span class="caption-body"> Looking at various aspects of Socrata for fiance with real data, made it possible to design a number of unique visualizations that spoke directly to the content being presented. This visualization was eventually refined and shipped as a part of Open Payroll.</span>
      </figcaption>
    </div>
  </div>

Along the way, I sought reviews, feedback and input from our customers as well as the Socrata team. This made it possible to quickly iterate on ideas, discover new possibilities, and uncover underlying constraints. One of those constraints was rooted in _fund-based accounting_, the prevailing structure of government finance and financial data structures.

The existing app provided a drill-in experience aligned to these hierarchical, finance data schemas. This turned out to be quite desirable to our customers, but lacked usability. The information was dense and employed odd interaction patterns. I didn’t want to throw out all of this goodness, so I built a fully functioning prototype using D3 to explore and test the proposed modifications.

<div class="artifact-wrapper">
  <div class="image-full">
    <img src="/work/images-finance/budget-animation-lg.gif" alt="Version 1" class="img-responsive">
    <figcaption>
      <span class="title">Chart animation. </span><span class="caption-body">I took the time to prototype, evaluate, and dial in the drill-in animation to help users "see" the hierarchical nature of the finance data displayed in the product's main stage.</span>
      </figcaption>
    </div>
  </div>

As we started to zero in on successful information designs, I started prototyping the in app experience, which would combine the data visualizations with the information architecture in a way that allowed users to forego an understanding of government finance and fluidly navigate through content. I took a great deal of care in honing and user testing the animations and drill-in experience to support these re-designed interactions.

<div class="artifact-wrapper">
  <div class="image-full">
    <img src="/work/images-finance/budget-hifi.png" alt="High-fi mockup" class="img-responsive">
    <figcaption>
      <span class="title">High fidelity mockup. </span><span class="caption-body">I created the polished designs in Illustrator. I make some general redlines and then worked 1:1 with the remote team through Skype to complete the designs.</span>
      </figcaption>
    </div>
  </div>

## Iteration & Outcomes
We shipped at the pace of one app per quarter and continued to iterate throughout the process. For example, we failed early on to understand the importance of making the drill in experience flexible enough for many new customers and they way they wanted to navigate the data structures. We iterated by introducing more flexibility to the data schema as well as the controls to support this complexity.

We also learned that customers had a huge desire to connect more narrative and context to specific aspects of their finance data and so later introduced capabilities for customers to configure and connect additional reporting and narrative to their apps.

The result was a set of apps that helps a wide range of cities, counties, states, and even the Obama White House communicate complex financial data through an easy to use and understand data tool.

### Media

**The Obama Whitehouse** used Socrata for Finance as a component of their fiscal transparency and responsibility initiative in early 2016.
<div class="artifact-wrapper">
  <div class="image-full">
    <img src="/work/images-finance/whitehouse-budget-tweet.png" alt="Tweet from the whitehouse" class="img-responsive">
    <figcaption>
      <span class="title">Tweet. </span><span class="caption-body"> The Obama Administration purchased and used Socrata for Finance to share the President's 2017 Budget.</span>
      </figcaption>
    </div>
  </div>

**Humbolt County California** weighs in on "how unbearably awful" new products and features are, or not. Verdict: doesn't suck.

[DOES THIS SUCK? Humboldt County Releases New Interactive Budget Visualization Thingy](https://lostcoastoutpost.com/2016/feb/1/does-suck-humboldt-county-releases-new-interactive/)


### Customer Quotes

**State of Massachusetts**
>"We literally cut out not just the middleman, we’ve cut out a whole group and a layer of bureaucracy around those public records requests that is going to allow free and open access to the data."

> --Tom Shack, State Comptroller


**Sedgwick County, KS**
>"The only word I can think of that describes this is impressive. I'm just blown away at how much utility is in this tool... It's a tremendous tool, I'm really impressed... this is a great thing for the public."

>--Jim Howell, District commissioner 
