# loops-and-logic-faq-accordion
This repository contains a Loops and Logic snippet designed to create an accordion structure for displaying FAQs on a WordPress site.

Problem:

I’m working with a custom post type called `loan-faq` and two taxonomies:

- `faq-topic` (e.g., "Auto Loan FAQs")
- `faq-type` (e.g., "FAQ", "SAQ", "MAQ")

The goal is to display posts on a taxonomy archive page, filtered by the current `faq-topic` and `faq-type` Currently, I'm using Loops and Logic to display the posts in an accordion format. Still, I need help implementing the correct query to filter the posts dynamically based on these two taxonomies.

Current Code

I've included the current accordion snippet [here](./accordion-snippet.html).

## What I Need Help With

1. How to filter posts correctly based on the current `faq-topic` term and `faq-type` term (e.g., "faq" for FAQs, "saq" for Should Ask Questions).
2. Suggestions for improving the performance and structure of the code.

I would greatly appreciate any help!
