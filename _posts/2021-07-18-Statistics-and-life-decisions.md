---
layout: post
comments: true
title: Statistics and life decisions
author: Leo dos Santos
permalink: /blog/:year/:month/:day/:title:output_ext
tag: 2021
excerpt_separator: <!--more-->
---

In a [post-truth](https://en.wikipedia.org/wiki/Post-truth) world riddled by misinformation, one might be compelled to look for science-based solutions to their predicaments: losing weight, raising a child, buying a new car, determining the age of a star, voting for a state representative, among other very common dilemmas. But science is messy. Results are many times inconclusive, have large uncertainties, and have many limitations. Today, we look at why you should be careful when making individual, science-based life decisions, especially when they involve statistics.

<!--more-->
{:refdef: style="text-align: center;"}
![Protection](/blog_assets/2021-07-18.jpeg "Protection")
{: refdef}

The main job of a scientist is to answer important questions. The answers we find need to be universal, otherwise there is no point in finding them out. Taking for example the contemporary case of searching for a vaccine against a pandemic: The very baseline of an effective preventive measure is that it be applicable to as many people as possible; a vaccine for a pandemic is no good if it only works for an individual and not for many people. Similar principles are also present in other sciences, such as astrophysics: One may be able to find a way to measure a particular physical parameter of an individual star, but if the method does not work for other stars, then its usefulness is very limited.

Another interesting example is what we sometimes call “anecdata”: Suppose a friend tells you of this new meditation technique that worked wonders for them to improve their anxiety levels. Whatever that may be, you would benefit from taking such an advice with a grain of salt, because that is only one data point. Now, things get more interesting if that meditation technique did have an important effect for many people, i.e., a sample. We are starting to have a semblance of statistics here. When a solution works for many people, we are compelled to take them more seriously. It is the results of science becoming reality to the benefit of all! Well, not so fast. Even when there is statistical evidence that shows something works at the level of a sample, that does not mean it will necessarily always work.

If you were born before the digital communication era, you may remember antennas. What is interesting about them is that they illustrate the concept of signal vs. noise really well. Say you were tuning your radio to a nearby station, and while doing that and hearing nothing but white noise, you bumped into something that sounded coherent. You found a signal, but it was muddled by noise. It is difficult to interpret the coherent sounds, but there is something in there. Or is there?

This happens a lot when dealing with large, complicated datasets and samples. At the bleeding edge of knowledge, there is a lot of noise and faint signals. So, how do we deal with this problem? It takes time to discern signal from noise, usually by improving experiments and building larger samples.

Alright, so there is a reason why I am writing about all this. See, it may come as no surprise to you, but companies want to sell us stuff. Recently, I saw an ad on YouTube that drew my attention. I will not name the product, but its premise is that will help you get in shape (i.e., lose weight) using behavioral psychology. They have something like 30 articles published in peer-reviewed journals, which is not something to shake a stick at, but I would advise care for the reasons I discuss below.

First, after digging on their website a bit, we can find a bit of statistics (no error bars, though): 64% of subjects lose at least 5% of body weight and 60% of subjects keep off their weight for at least one year. This information is not on the front page, nevertheless it is crucial to make an informed decision about buying the product or not. Essentially, when you sign up for it, you fill several forms that are supposed to “fit you into their data” and, based on this statistical fit, they find the best program that matches your profile. With a program success rate of approximately 60%, if we buy into their product, we should expect a chance of a little bit more than a coin toss to achieve our objective. 

I find this interesting because we actually do similar inferences in astrophysics. For instance, we are interested in measuring the ages of stars, but that is very difficult: they do not carry ID documents with their birth dates. So, we need to get creative to find investigative approaches that will reveal their ages. There are many ways to do it, but there is one called the “statistical method” or “kinematic age method.” Essentially, you can infer the age of a star in the Milky Way based on its velocity and position in relation to the Solar System. The reason why we can make such an inference is because our galaxy has a structure, and there is a correlation between the age of stars and their position and velocity in relation to the structure of our Galaxy. For instance, those close to the disk that defines our Galaxy tend to be younger than those far from it. Also, young stars tend to clump in moving groups, so if a group of them moves more or less on the same direction and are located near each other, it is possible that they have the same age.

However, the statistical or kinematic age method does not work well at the individual level, only at the level of a population or sample of stars. The reason is because the chances of an individual star having that exact inferred age are slim. On the other hand, if you have a large sample of them, the chances of, say, 50% of them having an age within a certain range of the inferred kinematic age are quite large. 

Let me illustrate this with a practical case. You may have heard of the exoplanetary system TRAPPIST-1. [It was all over the news back in 2017](https://exoplanets.nasa.gov/news/1419/nasa-telescope-reveals-largest-batch-of-earth-size-habitable-zone-planets-around-single-star/). It is also a really tricky system to pin down its age, for several reasons that we do not have time to go over. But the astrophysicists A. Burgasser and E. Mamajek gave it a try in an article published in the Astrophysical Journal \[[^1]\]. Among several techniques they applied the kinematic statistical aging method, which yielded an age estimate between 6.4 and 11.6 billions of years at approximately 70% confidence level. As you can see, this method is not very precise for an individual star, and the authors found a better age estimate was obtained when combining all the available methods together.

Going back to the weight-loss statistical program, similarly, the chances of you, as an individual, to be successful (with “success” defined by your weight-loss goal) are definitely not 100%. In fact, it is probably around 60%, if we consider the statistics I mentioned previously. But, at the population level, it is likely that their program is fairly successful. After all, making 60 people within a group of 100 lose weight and maintain it for a year is not an easy task, probably more difficult than measuring the age of a star!

Now, I feel compelled to say that this weight-loss program has a money-back guarantee policy, but they phrase it in a, let’s say, curious way: “If we don't change your population's behavior then it's free. Guaranteed.” I am not sure how to interpret this. So, do I get my money back if the program does not work for me? Or does a group of people get their money back if the program does not work for them as a sample? It seems dodgy. If they go for the individual policy, it means that they should give money back to approximately 40% of their clients, and that definitely does not sound good to a potential investor.

----------------

[^1]: Adam J. Burgasser and Eric E. Mamajek (2017). "On the Age of the TRAPPIST-1 System", The Astrophysical Journal, 845, 110. [doi:10.3847/1538-4357/aa7fea](https://www.doi.org/10.3847/1538-4357/aa7fea).
