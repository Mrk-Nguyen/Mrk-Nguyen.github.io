---
layout: post
title: Thinking Bayesian
category: statistics
excerpt: Shifting your thinking to what you've been doing already
usemathjax: true
---

![Blog Splash](/images/Thinking-Bayesian/splash.jpg)

Photo by [Jr Korpa](https://unsplash.com/@korpa?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/abstract?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)


## Introduction

I’m currently studying Bayesian Statistics to figure out alternative methods to  model events and marketing campaigns at work. A common model marketers use is the Marketing Mix Model to understand how different media tactics drive sales. From this understanding, we can play around with different marketing tactics to maximize sales.

The specific model that data scientists use is the [Bayesian Hierarchical Model](https://en.wikipedia.org/wiki/Bayesian_hierarchical_modeling).

In order to get to that level of modeling, I had to formally switch my thinking from a Frequentist approach to a Bayesian approach. Coming from a frequentist background, I’ve personally struggled to understand how Bayesian thinking relates back to comparing different statistical models, until I picked up Will Kurt’s book from [countbayesie.com](http://countbayesie.com), “Bayesian Statistics The Fun Way”.

## Frequentist vs Bayesian Approach

Will Kurt eloquently explained that statistics is simply a method to quantify probabilities using calculations and models. Living in a world of imperfect information and uncertainties, the best thing we can do as humans is to give a probability of what we expect things may happen. Statistics gives us an avenue to objectively reach a probability.

From there comes two common methodologies to reach a probability: Frequentist and Bayesian.

From a Frequentist perspective, probability represents a frequency with which something happens. We can assign a probability of rolling a 6 on a fair-sided die by counting how many times 6 shows up out of 1000 rolls. 

From a Bayesian perspective, probability represents how uncertain we are about a piece of information. We don’t need tests to run, memorize distributions, and design experiments that must be replicated. Probability is simply a numerical representation of what we believe in the world given the information we have; humans already innately do this. Bayesian statistics allows us to express our uncertainty and reasoning in a mathematical manner.

For certain activities and events such as flipping a coin, we can both use the Frequentist or Bayesian approach to express the probability that the coin lands on heads. However, calculating the probability that the COVID-19 pandemic will end in six months cannot be counted because there is only one COVID-19 pandemic occurring (hopefully only one ever) right now. We cannot simply count how many past COVID-19 pandemics ended in six months. The Bayesian approach would give us a methodology to reason and quantify the uncertainty COVID-19 ending in the next six months. 

## Bayesian Reasoning

Let’s step into how Bayesian reasoning works. At a high level, Bayesian reasoning revolves around creating hypotheses given observed data. We humans already do this in our daily lives. 

**Here is an example:**

Imagine you’ve come home and found your bicycle missing. Given this observation, you can come up with different theories of what happened to make sense of what you’ve seen such as:

- Roommate took your bike out again and forgot to tell you about it
- You actually forgot to take the bicycle back inside from the patio
- Someone broke into your home and stole our bicycle

For most folks, the likelihood of your forgetting to take your bicycle back inside is higher than a burglary occurring, unless you live in a neighborhood with high burglary rates.

As humans, our minds always need to make sense of what we’ve observed in the world. Observations by itself are useless; we need our minds to make insights, connections, and theories based on the observed data to help process our observations and make sense. 

In a more mathematical manner, making sense of what we see means we assign a high probability of what we observed given a hypothesis and our prior experience.

As we gather more data, we would change our beliefs to adjust for the newly given information.

**Let’s go back to the previous bicycle example:**

As you look for your bicycle throughout your home, you find out that the back door in your home is open with a broken lock.

Given this new data, you can then reason that the likelihood of burglary increased over the likelihood that you forgot to take the bicycle back inside from the patio. This change of beliefs given updated data, lies at the heart of Bayesian reasoning: **data informs belief.**

Now if we try to step through this line of thought, through the lense of statistical modeling, a belief or a hypothesis can be a model that helps explain the data we see. If we see that new data goes against our hypothesis, we simply update our hypothesis (the model) given the new data to reach a higher probability.

Here’s the key point in translating these abstract statements into something quantifiable: 

> Updating our beliefs given the new data is equivalent of getting a higher probability of our new hypothesis being correct given the new data. We compare the two probabilities of two hypotheses to figure out which hypothesis gives us a higher probability. 

This crucial piece of reasoning personally helped me solidify the crux of Bayesian thinking.

**Overall, remember this:**

We can just update our beliefs given new information. We can start off with a belief that is totally wrong, but as we gather more data, we can update our beliefs that make more sense given what we know so far. We've been doing this type of reasoning since we were born. Bayesian statistics simply gives us methods to help quantify our uncertainties and theories we constantly have as humans.
