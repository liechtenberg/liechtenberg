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
  <summary>Technical information</summary>
  
  <h2>Technologies Used</h2>

  <h3>Backend Management</h3>
  <ul>
    <li><strong>Pterodactyl Panel</strong>: I used <a href="https://pterodactyl.io">Pterodactyl</a> to manage the bots on the backend side. This open-source game server management panel provided a robust foundation for hosting and managing Discord bots with its Docker-based architecture.</li>
  </ul>

  <h3>Frontend & User Management</h3>
  <ul>
    <li><strong>WHMCS</strong>: I used <a href="https://www.whmcs.com">WHMCS</a> as a front-facing application for users. I decided to use it since it's pretty user-friendly for end users and has a lot of customization options and flexibility. One point to note is that it's not open source, so you can only use pre-defined addons/themes.</li>
  </ul>

  <h3>Containerization & Security</h3>
  <ul>
    <li><strong>Docker</strong>: I used Docker to containerize every bot in case of malware or other bad applications before I noticed and took them down. It's also very good to have a general overview of how much resources an instance is using, as well as to limit their total CPU/disk/memory to whatever you want.</li>
  </ul>

  <h3>Web Server & SSL</h3>
  <ul>
    <li><strong>Nginx with Let's Encrypt</strong>: I used nginx with Let's Encrypt for the web server and SSL certifications, ensuring secure connections for all users.</li>
  </ul>

  <h3>CDN & Performance</h3>
  <ul>
    <li><strong>CloudFlare</strong>: I used CloudFlare for proxying and caching to improve performance and provide additional security layers for the hosting service.</li>
  </ul>

</details>^

# Hostaris

Hostaris was a VPS hosting company where I specialized in managing financial disputes and chargeback resolution. I handled complex billing disputes and worked closely with payment processors to minimize financial losses until the company's closure.