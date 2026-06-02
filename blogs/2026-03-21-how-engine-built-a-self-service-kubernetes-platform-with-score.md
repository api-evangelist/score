---
title: How Engine Built a Self-Service Kubernetes Platform with Score
url: https://score.dev/blog/engine-self-service-kubernetes-platform-with-score/
date: '2026-03-21'
author: ''
feed_url: https://score.dev/index.xml
---
Recently, the Infrastructure team at Engine started a project that would change how every engineering team ships software. We were migrating dozens of services off a legacy container orchestration setup onto Kubernetes, and we had a choice to make: build another pile of bespoke tooling, or find an abstraction that could scale with us.
The real problem wasn’t Kubernetes itself. It was everything around it. Deploying a new service took days, sometimes weeks, and almost none of that time was spent on application code.
