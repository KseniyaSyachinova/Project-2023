---
title: Version control. Git.
subtitle: 

# Summary for listings and search engines
summary: Here you can learn about version control.

# Link this post with a project
projects: []

# Date published
date: '2023-03-16T00:00:00Z'

# Date updated
lastmod: '2023-03-16T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Academic

---

## Information

Git is a distributed version control tool that is a bit more difficult to use than SVN and other version control tools. To make it easier to understand, this article describes in detail the use of Git using graphics to quickly master Git. The main commands are shown in the figure.
From the figure above, it can be seen that Git is conceptually divided into 3 large areas: workspace, local warehouse and remote warehouse. There is also a temporary storage area, also called an index area. Let's see what each area does. The key point that Git reflects is distributed version control in that it has local storage. In fact, the usual version control work is done in the local library.

- Workspace: This is actually our working directory in the operating system. We can view the operating system's file management commands (for example, via the ls command in Linux).
- Local repository: There is a hidden directory in the workspace.git. This directory and its contents are also part of the workspace, but are a local Git repository. It is used to implement version control.
- Remote Warehouse: A remote warehouse is a warehouse stored on a remote server, mainly for multi-user collaboration.
- Temporary Storage area: The temporary storage area is usually stored in an index file (.git / index) in the "directory .git", so we sometimes refer to the temporary storage area as an index (index).
