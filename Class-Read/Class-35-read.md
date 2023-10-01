# JAMstack Overview

JAMstack (JavaScript, APIs, Markup) is a modern web development architecture and philosophy that offers numerous benefits. This README provides an overview of what JAMstack is, its components, advantages, examples, and tools to build JAMstack sites.

## What is JAMstack?

JAMstack is a web development architecture that consists of three core components:
- **Javascript**: Enables dynamic and interactive elements on web pages, often using UI frameworks like React, Vue, or Svelte.
- **APIs**: Leveraged for various purposes, such as authentication, search, and data retrieval, enhancing the user experience.
- **Markup**: The HTML content of a website, typically served statically, ensuring fast loading times.

JAMstack apps can range from simple static HTML websites to complex applications with dynamic features.

## JAMstack vs. Serverless

While JAMstack and serverless have similarities, they are not the same. Serverless refers to a cloud computing model, whereas JAMstack is a web architecture philosophy. JAMstack apps may or may not be serverless, depending on the backend infrastructure.

## Components of JAMstack

JAMstack is primarily composed of three components:

1. **Javascript**: Enables dynamic and interactive web elements using UI frameworks like React, Vue, or Svelte.
2. **APIs**: Enhances site functionality by interacting with various APIs for data retrieval and processing.
3. **Markup**: The HTML content served statically to clients, ensuring fast loading times.

These components empower developers to create scalable and high-performing web applications.

## Advantages of JAMstack

JAMstack offers several advantages, aligning with the AWS Well-Architected Framework's five pillars:

1. **Speed**: JAMstack apps load quickly since they are served as static files directly from a Content Delivery Network (CDN).

2. **Cost**: Hosting JAMstack sites is cost-effective due to the use of static assets and efficient content delivery.

3. **Scalability**: CDNs provide automatic scalability, ensuring your site handles increased traffic effortlessly.

4. **Maintenance**: Since JAMstack doesn't rely on servers, maintenance is minimal, with hosting providers handling most tasks.

5. **Security**: With no server to maintain, focus shifts to securing APIs and managing permissions for enhanced security.

However, the efficiency of JAMstack depends on how API requests are managed.

## Is Your Website a JAMstack Site?

A website can be considered JAMstack if it serves HTML statically without server-side rendering. It doesn't require the use of all three components (Javascript, APIs, Markup) and can be as simple as a static HTML file hosted on a server.

## Examples of JAMstack Sites

Here are some examples of JAMstack websites:

1. [freeCodeCamp](https://www.freecodecamp.org/): An educational platform built on Gatsby, combining static site generation with powerful APIs for learning to code.

2. [Impossible Foods](https://impossiblefoods.com/): The main website of Impossible Foods is powered by Gatsby, offering a fast and dynamic user experience.

3. [web.dev by Google](https://web.dev/): Google's web.dev resource center uses the 11ty static site generator for its content.

## Tools for Building JAMstack Sites

There are numerous tools available for building JAMstack sites. Here are some popular options:

### Constructing Your App

- [11ty](https://www.11ty.dev/)
- [Gatsby](https://www.gatsbyjs.com/)
- [Hugo](https://gohugo.io/)
- [Nift](https://nift.cc/)
- [Scully](https://scully.io/) (for Angular enthusiasts)

Start with Gatsby if you're unsure, as it's beginner-friendly and comes with many starter templates.

### Serving Your App

- [AWS](https://aws.amazon.com/)
- [Azure](https://azure.microsoft.com/)
- [Google Cloud Platform (GCP)](https://cloud.google.com/)
- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)
- [Surge](https://surge.sh/)
- [Zeit](https://zeit.co/)

Netlify is a great choice for effortless deployment, especially when combined with Gatsby.

### Making Your App Dynamic

To make your JAMstack app dynamic, you can utilize various tools and APIs. The choice depends on your specific requirements.

