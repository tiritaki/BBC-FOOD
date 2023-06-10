# BBC Food Website Clone

This project is a clone of the [BBC Food website](https://www.bbc.co.uk/food/collections/quick_vegan_recipes), developed with the goal of creating a practical and efficient interface for browsing and sharing food recipes.

## Issue 🤔

We've identified a common issue in the current development process: developers are directly embedding recipe content into HTML files. This means intertwining data (recipes, ingredients, etc.) with the presentation layer (HTML structure and styling). We want to be able to make changes to the recipe data without touching the presentation layer. 

## Proposed solution

To overcome this issue, we're going to update this project to make use of a [Static Site Generator (SSG)](https://www.netlify.com/blog/2020/04/14/what-is-a-static-site-generator-and-3-ways-to-find-the-best-one/). With an SSG, we can separate the content from the presentation. Content, such as recipes and ingredients, can be stored in a simple, easy-to-update format like Markdown or JSON. The SSG will then transform this data into a fully-structured and styled website. In this project, we're going to use [Eleventy](https://www.11ty.dev/)

## First steps

1. Template this repository
2. Clone issues from the original repo other to your template
3. Start with the following issues first: 
- https://github.com/CodeYourFuture/bbc-food/issues/79
- https://github.com/CodeYourFuture/bbc-food/issues/75
