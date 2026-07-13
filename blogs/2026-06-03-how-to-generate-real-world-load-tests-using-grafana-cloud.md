---
title: "How to generate real-world load tests using Grafana Cloud k6 and production telemetry"
url: "https://grafana.com/blog/how-to-generate-real-world-load-tests-using-grafana-cloud-k6-and-production-telemetry/"
date: "2026-06-03"
author: "Matt Wimpelberg"
feed_url: "https://grafana.com/blog/index.xml"
---
For many development teams, a load test starts with a set of assumptions. You pick 100 virtual users because it sounds reasonable. You ramp for 30 seconds because that's what the tutorial showed. You set a 500ms threshold because it feels like a good target. The test passes, you ship the release, and production falls over at 6 p.m. on a Tuesday because your synthetic load never resembled how real users interact with your application. The good news is that, if you're running Grafana Cloud , you...
