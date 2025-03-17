# Student Profile Builder
A Progressive Recommendation System to suggest Educational resources(articles, YT videos and Mooc courses) for students based on their preference to build their profile in the field of Computer Science.

## Technologies Used
* Python
* NLTK
* Sci-Kit Learn
* PyQt5 (Front end)

## Background
To simulate an actual Recommendation engine, data for Articles, Videos and Mooc Courses were already downloaded and scraped from the internet. A set of tags were assigned to each item in these resources manually.

## Functionalities
This project implements a personalized recommendation engine that suggests videos, articles, and courses based on user preferences using a <strong>Content-based filtering algorithm</strong>.

* Each user has a profile of tags that evolves dynamically based on their interactions.
* Initially, recommendations are based on user-selected interests on the GUI.
* Every time a user views a resource, its tags are added to their profile, refining future suggestions.
* Recommendations are generated using Cosine Similarity, ensuring users receive content that closely matches their evolving interests.
* The system continuously learns from user behavior, improving recommendations over time.

