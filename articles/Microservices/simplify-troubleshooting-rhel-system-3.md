---
article_heading: Simplify troubleshooting RHEL system configurations with Red Hat
  Insights Drift service
article_date: 2020-07-06T18:30:00.000+00:00
article_tags:
- Redhat Canada
- Redhat
- Redhat Forum
article_authors:
- author_name: Rajith Attapattu
  author_image: "/images/rajith.jpg"
  description: Rajith has extensive experience in architecture & development of large
    scale enterprise systems for the financial services and telco industry. Previously,
    Rajith was an enterprise architect at Red Hat helping customers build successful
    solutions using Red Hat technology. Prior to that, he spent a number of years
    in engineering building middleware products.
  job_title: CTO/Managing Partner
- author_name: Asiri Warnakulasuriya
  description: Asiri has held lead positions at prestigious corporates prior to the
    engagement with Randoli. His background is in developing and architecting world-class
    Enterprise Software. He holds Bachelor's and Master's degrees from the University
    of Moratuwa, Sri Lanka. Asiri is a Certified Scrum Master and has a lot of experience
    in managing software development projects carried out in Sri Lanka for offshore
    clients. Prior to Randoli he was holding a lead position at Sysco, rearchitecting
    aging software systems to give Sysco Corp. a competitive advantage.
  job_title: 'Director of Engineering '
  author_image: "/images/asiri-bw.jpg"
article_background_image: "/images/article-cover.png"
title: Simplify-troubleshooting-RHEL-system-3
article_topic: Microservices
article_card_image: "/images/article-card-img.png"
article_category: Microservices
article_short_description: Multi-fact filtering gives you the power to create comparisons
  that drill down to the most important elements to you, negating the need to swap
  back and forth between multiple filters.

---
Drift, a feature within Red Hat Insights, can help with managing and troubleshooting issues across a number of systems. Red Hat Insights is a Red Hat Enterprise Linux (RHEL) configuration analysis service that is available as part of your RHEL subscription.

System administrators can use Drift to compare configurations, define baselines, and ultimately perform root-cause analysis of issues during troubleshooting. Since system configurations tend to vary and drift away from initial defined standard operating environments, it is important for users to be able to immediately check if a problem can be related to any differences from the recommended configuration.

In this post, we will explore some new features recently added to the Drift UI in response to customer feedback, including requests to help troubleshoot faster.

### Multi-fact Filtering

Multi-fact filtering gives you the power to create comparisons that drill down to the most important elements to you, negating the need to swap back and forth between multiple filters. It also proves to be useful for quickly comparing facts related to a specific issue while troubleshooting, and filtering out un-related facts.

Previously, filtering facts in a comparison was limited to a single fact name input (an example is shown in the first figure). As you entered a fact you wanted to filter by, the comparison table would filter out any fact name that didn’t match the combination of characters you had typed, with each keystroke.

Substrings would also be matched (e.g., typing "kern" will give you "kernel" and "os_kernel_version"). And, if you wanted to filter a category name (e.g., installed_packages), just typing the full name of the category would bring it up by itself with all of its sub facts present underneath.