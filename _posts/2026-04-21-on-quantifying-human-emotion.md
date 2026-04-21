---
title: "On Quantifying Human Emotion"
date: 2026-04-01
category: research
tags: [human-robot-interaction, emotion, modeling, machine-learning]
excerpt: "How can we translate emotions into the language of computers?"
---

The question at the center of my work right now is deceptively simple: *what makes up an emotion*?

You might say, "Well, are you happy or sad? How strongly do you feel that way?" While this is a good start, what about anxiety? It's not necessarily sad, happy isn't right either, and it's certainly not a weak feeling. What about depression? It's sad but somehow more than sad; it's a strong feeling of no feeling. How can we capture complex emotions like these?

In 1980, James A. Russel came up with (and validated!) a novel idea of how to classify emotion: the circumplex model of affect. The concept is fairly simple where emotions are a combination of two elements: valence and arousal. Valence represents how positive or negative, pleasant or unpleasant, an emotion feels. Arousal is how activated or excited your emotions are. The chart below shows rough sectors of validated emotions using valence-arousal as the axes.

<figure class="post-figure">
	<img src="/assets/images/circumplex-model.jpg" alt="Russell circumplex model">
	<figcaption>The Russell circumplex — valence on the x-axis, arousal on the y-axis.</figcaption>
</figure>

For example, in this model, neither pleasant nor unpleasant with low activation would be considered sleepy (somewhere between fatigued and calm). Anxiety, for example, would fall somewhere between mildly unpleasant to mildly pleasant valence with very high arousal (nervous through alert sections on the chart). Depression, on the other hand, is characterized by both low arousal and unpleasant valence.

Over the decades, many studies have used this model or tried to form a new model but came up with similar results. That's a beautiful thing about this model: it's tried and true. Another beautiful thing about this model is that the two axes of valence and arousal allow us to model emotion as coordinates on a circle, and that's math a computer can understand. This is the model I've chosen to power the next step of my work: *with physiological measurements (i.e. heart rate, sweat level, breathing rate, or sleep analysis) and surveys, how can we measure valence and arousal for computers to understand human emotions?*

Once computers can understand how we're feeling, they can be better teammates. For example, if you are working with a robot on a task and some tasks are assigned to you while other tasks are assigned to the robot, the robot can understand your emotions to give you tasks that make you happy or calm, while avoiding giving you tasks that make you stressed or defeated. Or, instead, perhaps they do give you tasks which challenge you and make you stressed, but not more than you can handle with lighter tasks to help reduce your emotional workload. Depending on the application, this model of emotion can be flexible, so robots can use the same information but respond in different ways. 

By using data to model emotions in a language robots can understand, we're designing machines that serve humans—not the other way around.