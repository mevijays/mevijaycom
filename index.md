---
layout: default
title: Home
---

# Vijay Vishwakarma

## DevOps Cloud Practice Lead

Welcome to my personal portfolio website. Here you can find information about my expertise, certifications, and blog posts.

### Expertise
- DevOps
- Cloud Computing
- Automation
- Continuous Integration/Continuous Deployment (CI/CD)

### Certifications
- AWS Certified Solutions Architect
- Google Cloud Professional DevOps Engineer
- Microsoft Certified: Azure DevOps Engineer Expert

View all certifications

### Blog
Read my latest posts:

{% assign posts = site.posts | sort: 'date' | reverse | limit: 5 %}
{% for post in posts %}
1. [{{ post.title }}]({{ post.url }})
{% endfor %}