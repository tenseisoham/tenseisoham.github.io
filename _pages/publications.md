---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<style>
/* Publications Page Specific Styles */

.paper-box {
    display: flex; /* Use flexbox for horizontal layout */
    align-items: flex-start; /* Align items to the top */
    background-color: #2e343a; /* Dark background as in the image */
    color: #e0e0e0; /* Light text color */
    padding: 20px;
    margin-bottom: 25px; /* Space between publication entries */
    border-radius: 8px; /* Slightly rounded corners */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Subtle shadow */
}

.paper-box-image {
    flex-shrink: 0; /* Prevent the image from shrinking */
    margin-right: 20px; /* Space between image and text */
    width: 150px; /* Fixed width for the image container */
    height: auto; /* Maintain aspect ratio */
}

.paper-box-image img {
    max-width: 100%; /* Ensure image fits within its container */
    height: auto; /* Maintain aspect ratio */
    border-radius: 4px; /* Slightly rounded corners for the image */
}

.paper-box-text {
    flex-grow: 1; /* Allow text content to take up remaining space */
}

.paper-box-text a {
    color: #87ceeb; /* A light blue for links, similar to the image */
    text-decoration: none; /* No underline by default */
}

.paper-box-text a:hover {
    text-decoration: underline; /* Underline on hover */
}

.paper-box-text strong {
    color: #ffffff; /* White for strong text/title */
}

.publication-badges {
    margin-top: 10px;
    margin-bottom: 15px; /* Space below badges */
}

.badge {
    display: inline-block; /* Make badges sit next to each other */
    padding: 5px 10px;
    border-radius: 5px;
    font-size: 0.9em;
    font-weight: bold;
    margin-right: 10px; /* Space between badges */
    text-transform: uppercase; /* Uppercase text */
}

.badge.accepted {
    background-color: #daa520; /* Golden yellow for "Accepted" badge */
    color: #ffffff;
}

.badge.arxiv-link,
.badge.github-link {
    background-color: transparent; /* No background for arxiv/github links */
    border: 1px solid #87ceeb; /* Border matching link color */
    color: #87ceeb; /* Text color matching link color */
    padding: 4px 9px; /* Adjust padding to look similar to accepted badge */
}

/* Adjust font sizes and line heights for better readability */
.paper-box-text p {
    font-size: 0.95em;
    line-height: 1.6;
    margin-bottom: 10px;
}
</style>

<div class='paper-box'>
  <div class='paper-box-image'>
    <img src='{{ site.baseurl }}/assets/img/adaptai.JPG' alt="Paper Thumbnail">
  </div>
  <div class='paper-box-text' markdown="1">
    <a id="adaptai-paper" href="https://arxiv.org/abs/2503.09150">
      **AdaptAI: A Personalized Solution to Sense Your Stress, Fix Your Mess, and Boost Productivity**
    </a>
    <br>
    Rushiraj Gadhvi, Soham Petkar, Priyansh Desai, Shreyas Ramachandran, Siddharth Siddharth
    <br>
    <div class="publication-badges">
      <span class="badge accepted">Accepted CHI'25 LBW</span>
      <a href="https://arxiv.org/abs/2503.09150" class="badge arxiv-link">[arXiv]</a>
      <a href="https://github.com/gadhvirushiraj/AdaptAI" class="badge github-link">[GitHub]</a>
    </div>
    <p>Personalization is a critical yet often overlooked factor in boosting productivity and well-being in knowledge-intensive workplaces to better address individual preferences. Existing tools typically offer uniform guidance—whether auto-generating email responses or prompting break reminders—without accounting for individual behavioral patterns or stress triggers.</p>
    <p>We introduce **AdaptAI**, a multimodal AI solution combining egocentric vision and audio, heart and motion activities, and the agentic workflow of Large Language Models (LLMs) to deliver highly personalized productivity support and context-aware well-being interventions.</p>
    <p>AdaptAI not only automates peripheral tasks (e.g., drafting succinct document summaries, replying to emails, etc.) but also continuously monitors the user's unique physiological and situational indicators to dynamically tailor interventions—such as micro-break suggestions or exercise prompts—at the exact point of need.</p>
    <p>In a preliminary study with 15 participants, AdaptAI demonstrated significant improvements in task throughput and user satisfaction by anticipating user stressors and streamlining daily workflows.</p>
  </div>
</div>