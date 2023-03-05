# Student Profile Builder
A Progressive Recommendation System to suggest Educational resources for students based on their preference to build their profile in the field of Computer Science. The System uses a Content-based Filtering algorithm to recommend articles, YT videos and Mooc courses

## Technologies Used
* Python
* NLTK
* Sci-Kit Learn
* PyQt5

## Content-based Filtering Algorithm
In order to simualate an actual Recommendation engine, data for Articles, Videos and Mooc Courses were already downloaded, scraped from the internet. A set of tags are first assigned to each of these resources manually. Every user signing in the platform will have thier own profile of tags mapped to their profile. They'll be able to get suggestions for a list of videos/ articles/ courses based on their initial preferences. Everytime a user clicks on a resource to view it, the tags o the resource gets mapped to the user. Following this, new resources are suggested based on the similarity(Cosine Similarity) between the uesr's tags and the tags of the unseen resources(Other resources in the remaining dataset at the moment). Resources whose tags match the most with the user are automatically recommendedthe next time the user visits the portal.

