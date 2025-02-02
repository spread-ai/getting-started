---
title: Getting started
description: The overview page for the Getting Started section, which has learning content for using the SPREAD Platform.
hide:
  - navigation
  - toc
  - path
---

<!--
README

For guidance on how to write documenation, see https://dev.stage.spread.ai/docs/contributor/guide.html. Contact Documentation when this document is ready for review.
-->

<style>
     .md-typeset h1, .md-source-file, .md-typeset hr {
          display: none;
     }

     /* Disable the definition tooltip on this page */
     abbr {
          pointer-events: none;
          text-decoration: none;
          color: inherit;
          background: none;
          border-bottom: none !important;
     }

     .md-main__inner {
          margin: 0 !important;
     }

     .md-content__button {
          margin: 8.25px !important;
     }

     article.md-content__inner {
          margin: 0 !important;
          padding-bottom: 3em;
          padding-top: 3em;
     }

     .header {
          width: 100vw;
          background-image: linear-gradient(0deg,#d9e8f9,white);
          min-height: 45vh;
          padding-bottom: 2em;
     }

     .header > .right-header-course {
          display: inline-block !important;
          text-align: left;
          font-weight: 600;
          width: 40vw;
          padding-left: 10vw;
     }

     .header > .left-header-course {
          display: inline-block !important;
          text-align: right;
          min-width: 40vw;
          padding-left: 10vw;
     }

     li {
          list-style-type: none !important;
     }

     nav.md-footer__inner {
          display: none !important;
     }
</style>

<div class='header'>

<div class='right-header-course'>
	<div style='color: var(--primary)'>Course</div>
	<div style='padding-top: 1rem; padding-bottom: 1rem; font-size: 2.5rem; line-height: 1.3' markdown>Intro to the SPREAD Platform</div>
	<div style='line-height: 1.5; font-weight: 400; font-size: 0.7rem'>Learn how to use the SPREAD Platform, from importing data to creating a simple application to writing data to the Engineering Intelligence Graph.</div>
     <br>
     <div>
          <a href="module-1/what-is-spread.html" class="md-button md-button--primary">Get started</a>
     </div>
</div>

<div class='left-header-course'>
     <img src="src/car-diagnosis-demo.png" alt="Image of a car undergoing diagnostics" width="400" class="skip-lightbox">
</div>

</div>

<br>
<br>
<br>

<div class='grid cards' style='max-width: 90vw !important; margin: auto' markdown>

- :material-book-open:{ .lg .middle } __What you'll learn__

    ---

     - :octicons-arrow-right-24: What the Engineering Intelligence Graph (EI Graph) is
     - :octicons-arrow-right-24: Creating a basic Studio application UI
     - :octicons-arrow-right-24: Querying data in the EI Graph from Studio
     - :octicons-arrow-right-24: Publishing a Studio application
     - :octicons-arrow-right-24: Connecting widgets for shared interactions in a Studio application
     - :octicons-arrow-right-24: Writing data to the EI Graph from Studio

- :material-account-school:{ .lg .middle } __Pre-requisites__

    ---

     - [x] Access to a SPREAD Platform instance with Studio.
     - [x] A basic understanding of JavaScript.
     - [x] A basic understanding of [GraphQL](https://graphql.org/learn/).
     - [x] A [GitHub account](https://github.com/signup).

- :material-view-list:{ .lg .middle } __Lessons__

    ---

     - [:octicons-arrow-right-24: Module 1: Understanding the SPREAD Platform](module-1/what-is-spread.md)
          - [What is SPREAD?](module-1/what-is-spread.md)
          - [What is the Engineering Intelligence Graph?](module-1/what-is-eig.md)
          - [Creating a Studio application](module-1/creating-a-studio-application.md)
     - [:octicons-arrow-right-24: Module 2: Creating a viewing application](module-2/understanding-spread-information-architecture.md)
          - [SPREAD information architecture](module-2/understanding-spread-information-architecture.md)
          - [Querying SPREAD](module-2/querying-spread.md)
          - [Creating a display application](module-2/creating-a-display-application.md)
     - [:octicons-arrow-right-24: Module 3: Creating data visualizations](module-3/studio-data-visualizations.md)
          - [Studio data visualizations](module-3/studio-data-visualizations.md)
          - [Creating data visualizations](module-3/creating-data-visualizations.md)
     - [:octicons-arrow-right-24: Module 4: Creating an authoring application](module-4/understanding-graphql-mutations.md)
          - [Understanding GraphQL mutations](module-4/understanding-graphql-mutations.md)
          - [Creating an authoring application](module-4/creating-an-authoring-app.md)

</div>
<br>
<br>
