---
layout: post
title: Drastically Improve Your Performance Testing With SmartLoad
published: true
category: product
tags: [ engineering, documentation ]
excerpt: This is our first post detailing why we built SmartLoad, and how we hope to improve the lives of performance engineers across the globe.
---

App users expect websites to respond quickly, and work as intended without any lag or performance issues. Good user experience is at the core of digital transformation, and customers are becoming increasingly intolerant of brand experiences that don't align with their expectations, particularly with regards to speed. Imagine how frustrated we get when we wait longer than 45 seconds for our favorite Netflix shows to stream?

It's no wonder then that performance testing has become an almost ubiquitous need for product that was to scale their usage and growth. Having a poor performance testing strategy goes beyond just user retention, as research shows how fixing performance bugs in productions costs 50% more to fix. Clearly, having poor performance of apps costs money and affects user growth, two of the biggest metrics of success for most businesses.

# But Is Performance Testing Easy?

Theoretically, it should be. It's essentially identifying performance bottlenecks by simulating concurrent usage of your apps across a set of expected business. Sounds fairly straightforward, but in practice, this is hindered by outdated testing processes that need to fit in with overly complicated tools.

## Outdated Processes

Traditionally, performance testing have relied heavily on rigorous processes that add huge overhead to the core development workflow. As teams adopted agile methodologies to move faster, testing, especially performance testing always fell behind due the associated overhead costs. It became increasingly difficult to have consistent tests, particularly performance

The Shift-Left methodology has become popular due to this very reason of developing a culture of involving testing early on in the development and delivery process of software applications. For the Shift-Left methodology to work, teams would need lightweight and flexible tools that fit the speeds of their software development counterparts. This is where the second problem arises.

## Complicated Tools

The available tools for performance testing also add huge complications given their steep learning curve. Many popular tools like Loadrunner or JMeter have been built with the traditional performance tester in mind, characterized by a waterfall approach to development and testing, and investing lots of time and effort to configure and string together performance tests. These tools were not built for the modern development and testing team focused on speed, agility and ease of use, who don't have the time to invest in creating cumbersome test scripts.

Many tools also require you to know some form of scripting to create your test scripts. Be it Selenium, Mocha or Gatling, knowing to script was foundational to the test engineer's arsenal when creating performance testing scripts. Scripting a test from the start can take a lot of time, and if your development teams aren't already used to this, will require them to learn all of this from the ground up, and that takes a huge amount of time.

As development cycles get shorter, releases get quicker, and customer expectations on performance goes up, it becomes imperative for teams to get their performance testing strategy implemented with tools that fit their development velocities without adding overhead and expecting learning curves over a week.

# A Faster Way To Performance Test With SmartLoad

The frustration of the complicated tools and processes forced us to look for a better way of doing performance testing. What if there was a lightweight load testing platform that required no setup and downloads, with almost zero learning curve? What if this tool can fit into any development cycle while simultaneously allowing teams to record test scripts without any configuration, maintain and reuse these scripts without additional updates, and analyze the results of the test and ensure there's no performance bottlenecks in your websites?

This belief of a better way to performance test led us to develop SmartLoad. Our mission with SmartLoad was to allow teams to drastically minimize the effort it takes to create performance test scripts, and produce accurate, reliable results from real browsers, to maximize your app's performance. Let's dissect this and elaborate on what we mean.

## Drastically Reducing Time To Create Test Scripts

SmartLoad allows you to record test scripts with real Chrome browsers that get spun up on real servers we manage on the cloud, without any scripting or code. You can record tests by interacting with the browsers inside the SmartLoad platform, and create business transactions just like how your end users would, without having to start with a complicated script or framework. Of course, you can always work with the Selenium framework of the script you recorded in SmartLoad, and configure different steps, iterations and think-time to mimic real-world usage and validate your website's availability with assertions.

## Producing Actionable, Reliable Results

Traditional load testing tools emulators to simulate concurrent usage. Data from emulators need to be translated by your team to some form of developer friendly verbiage in order to be understood and actionable. This just means more time spent by your test engineers learning how best to relay the produced data to your development teams and fix performance bottlenecks.

SmartLoad overcomes this issue by using real browsers to record test scripts, with actual data from the network itself. This just happens to be the exact data your engineering team would need to understand the performance of your webapps. This data is also much more reliable since we get this from real browsers on actual servers, and not emulators. Debugging in real time is also a unique capability, that allows you to see performance issues like network lags and memory defects across every single element of your website's DOM, and isolate bottlenecks on the fly!

# Closing Notes

Load testing shouldn't be a complicated and cumbersome process. We aim to empower anyone involved in the delivery of a webapp, be it the technical engineering team, or your creative marketing team, to load test their webapps and ensure their performance under any condition.

Unlike other tools that require some form of browser plugin or app download to perform the test script recording, SmartLoad can fully run on the cloud.  SmartLoad is currently in beta, and can performance test webapps for now. Any input you can provide us will help us go a long way in building a valuable product to ensure your app's reliability.

<a class="btn btn-primary btn-lg" href="https://app.smartload.io/" role="button" aria-pressed="true">Try It Now</a>
