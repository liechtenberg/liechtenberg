---
permalink: /projects/
title: "Projects"
author_profile: true
redirect_from: 
  - /projects.html
  - /project
---

# ApexCloud

ApexCloud was a small side-gig where I offered free Discord bot hosting services to people who needed it. It was used by around 12,000 users at its peak.

<details>
  <summary>Technical Implementation Details</summary>
  
  ## Technologies Used

  ### Backend Management
  - **Pterodactyl Panel**: I used [Pterodactyl](https://pterodactyl.io) to manage the bots on the backend side. This open-source game server management panel provided a robust foundation for hosting and managing Discord bots with its Docker-based architecture.

  ### Frontend & User Management
  - **WHMCS**: I used [WHMCS](https://www.whmcs.com) as a front-facing application for users. I decided to use it since it's pretty user-friendly for end users and has a lot of customization options and flexibility. One point to note is that it's not open source, so you can only use pre-defined addons/themes.

  ### Containerization & Security
  - **Docker**: I used Docker to containerize every bot in case of malware or other bad applications before I noticed and took them down. It's also very good to have a general overview of how much resources an instance is using, as well as to limit their total CPU/disk/memory to whatever you want.

  ### Web Server & SSL
  - **Nginx with Let's Encrypt**: I used nginx with Let's Encrypt for the web server and SSL certifications, ensuring secure connections for all users.

  ### CDN & Performance
  - **CloudFlare**: I used CloudFlare for proxying and caching to improve performance and provide additional security layers for the hosting service.

</details>