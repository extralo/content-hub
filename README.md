# ExTraLo content-hub


## A headless and decoupled Content Management Systems (CMS)


A Decoupled CMS, also known as a "Headless" CMS, is a modern content management approach that provides a way to manage and deliver content without being tied to a specific output/rendering like a traditional CMS.
In a traditional (coupled) CMS, the backend, where the content is created and managed (Content Management Backend or Admin Panel), and the frontend, where the content is served to the users (Website or Web Application), are "coupled" together into a single application.
In contrast, a decoupled CMS separates these two layers. Here's an overview of how it works:

* **Content Management Backend**: This is where content is created, read, updated, and deleted - commonly referred as CRUD operations. Content might be anything like blog posts, photos, user accounts, or any other data that the app might use.
* **Content Delivery**: In a decoupled CMS, the delivery of content to the end-users (the "front end") is handled separately from the content management backend. The CMS uses an API (usually RESTful or GraphQL) to expose the content to be fetched programmatically. This decoupled nature allows freedom in how the content is used and where it is displayed. It could be a website, a mobile app, a digital signboard, or even a VR/AR environment.

Benefits of a decoupled CMS include more flexibility in content presentation, future-proof content, and often better performance and security than traditional CMSs. Moreover, frontend developers are able to work using the technologies they prefer because they are not tied to the technology used by the backend CMS.