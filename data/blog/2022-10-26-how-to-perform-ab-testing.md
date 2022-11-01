---
title: How to Perform A/B Testing
author: Gautham Vemulapalli
date: '2022-10-27'
tags: ['product', 'how-to']
summary: Learn how to perform A/B tests for you product.
---

<TOCInline toc={props.toc} asDisclosure toHeading={3} />

### A/B Testing

**Framework**

1. Develop a hypothesis
2. Decide if the test is worth it
3. Design the test
4. Run the test
5. Measure the results

##### 1. Develop a hypothesis

**Example**

> If we use an orange button, we'll see an increase in conversions since other SaaS companies are using orange buttons outperform other colors.

_We need to validate there's a clear hypothesis before starting an A/B test._

Useful questions to ask ourselves:

1. How do you think users will interact with each variation?
2. What do you expect the results to be?
3. Why do you think that?

##### 2. Decide if the test is worth it

Useful questions to ask ourselves:

1. What is the potential impact of running the test? Will the results of the test drive any significant results?
2. What is the time and effort to implement the test?

##### 3. Design the test

1. Determine target audience (control group, geographic region, etc)

   ```
   Group A: 30%
   Group B: 70%
   ```

2. How long will we run the test for? How long would it take to see a statistical significance?
3. What will the test look like?
4. Which tool to use?

##### 4. Run the test

Basically, push the button and periodically monitor the results until you've hit the predetermined length of time or we have anough of a sample size to take action on the results.

##### 5. Measure the results

1. Look at which group drove better metrics (clicks, conversion rate, etc)

### Common tools

**Google Optimize**

- Free option for A/B testing if you have Google Analytics setup

<iframe
  width='560'
  height='315'
  src='https://www.youtube.com/embed/l3thoiqvH6E'
  title='YouTube video player'
  frameborder='0'
  allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture'
  allowfullscreen
></iframe>

**LaunchDarkly**

- Makes experimentation part of the normal delivery process
- Builds A/B tests into feature flags
- Each time you launch a new feature, it's wrapped in a feature flag.
- You can launch different variations and LaunchDarkly will identify the winning variant, then you can roll out the ideal version to all instances.

<iframe
  width='560'
  height='315'
  src='https://www.youtube.com/embed/0evo68QmcJ4'
  title='YouTube video player'
  frameborder='0'
  allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture'
  allowfullscreen
></iframe>
