---
permalink: /
excerpt: "About me"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<img src="/images/4.png" alt="Aditya Kumar" class="profile-pic">

# Aditya Kumar

<p class="subtitle">Software Engineer · Bangalore, India</p>

<div class="section">
    <div class="links">
        <a href="mailto:adityak2920@gmail.com">Email</a>
        <a href="https://linkedin.com/in/adityak2920">LinkedIn</a>
        <a href="https://github.com/adityak2920">GitHub</a>
    </div>
</div>

Software Engineer with **5 years of experience** building large-scale systems serving 3M+ users. **High-agency engineer** with end-to-end ownership, from identifying opportunities and navigating stakeholder requirements to driving technical execution and deployment. Deep expertise in backend systems and Machine Learning infrastructure at scale.

## Experience

**Kirana Club** · Software Development Engineer · *Jan 2023 -- Present*
- Architected and led the development of a **unified e-commerce platform** (Go, Next.js) that orchestrates the complete order lifecycle for thousands of daily transactions, integrating a custom Order Management System (OMS) with automated logistics allocation and warehouse management for hundreds of sellers.
- Developed a centralized suite for SKU cataloging, automated pricing, and coupon management alongside a real-time analytics platform to track sales trends and supply chain bottlenecks, reducing order processing time from **hours to near-instantaneous** while significantly improving delivery success rates.
- Built an end-to-end customer support platform with designing the ticketing interface, agent workflow, and automated routing/priortisation logic to manage thousands of daily inquiries. Streamlined processes across users, agents, and sellers to resolve exceptions, reducing Turnaround Time (TAT) from **hours to minutes** and directly driving increased repeat orders.
- Engineered a high-performance spatial service using SQL spatial indexing and **H3 Grid Indexing** with bounding box optimizations, achieving **<30ms latency** for reverse geocoding and **<100ms p99** for "Nearby Users" queries.
- Designed and deployed a **self-managed ClickHouse** cluster to handle **20M+ daily events** for high-velocity impression data, optimizing data modeling and partitioning for high-throughput analytics.

**Retail Pulse** · Machine Learning Engineer · *Aug 2020 -- Jan 2023*
- Architected and deployed a multi-stage product recognition pipeline for Indian retail environments combining YOLO object detector(trained on 25k+ images), DML embeddings(trained on 5M+ images) with FAISS-based matching, quality filtering, and screen recapture detection. The pipeline achieved **92% product-level** and **85% SKU-level accuracy** across **25,000+ SKUs**, processing **10M+ images/month** in production.
- Developed a client-facing analytics platform visualizing real-time store execution metrics, enabling major FMCG clients to monitor shelf compliance and stock availability.

**Sparrosense** · Data Science Intern
- Developed self-supervised steel pouring classification in steel manufacturing process.

**Humonics Global** · Data Science Intern · *Jun 2019 -- Jan 2020*
- Built instance segmentation models for automated car insurance claims achieving 0.8 mAP and optimized the inference pipeline using TorchScript and C++ to achieve a **1.5x speedup** in production.

## Technical Skills
- **Languages:** Golang, Python, JavaScript/TypeScript, SQL, C++
- **Backend & Systems:** FastAPI, Node.js, Next.js, gRPC, Docker, RabbitMQ, System Design
- **Databases & Storage:** PostgreSQL, Redis, Firebase, ClickHouse, Elasticsearch, Uber H3
- **Machine Learning:** PyTorch, Computer Vision (YOLO, OpenCV), Deep Metric Learning, Model Serving

## Education
**Guru Gobind Singh Indraprastha University** · New Delhi, India
*B.Tech in Electronics and Communication Engineering* · 2017 -- 2021

## Achievements
- **Open Source Contributor:** Contributed to OpenCV library with merged PRs.
- **Scholarship:** Recipient of Secure and Private AI Scholarship from Facebook and Udacity.

## Recent Blog Posts
<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
