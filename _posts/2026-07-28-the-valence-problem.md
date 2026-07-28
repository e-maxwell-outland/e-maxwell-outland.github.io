---
title: "The Valence Problem"
date: 2026-07-28
category: research
tags: [human-robot-interaction, emotion, modeling, machine-learning]
excerpt: "Why measuring valence from non-obtrusive physiological signals isn't possible"
---

In a previous post titled "On Quantifying Human Emotion", I was pondering how to answer the question: *what makes up an emotion*? While it doesn't describe every aspect of an emotional episode, the Russel circumplex model is a pretty good model of the basic, raw emotion before your brain puts that feeling into your surrounding context (Russell, 1980). It's a good model of the "proto-emotion", so to speak (called core affect in the literature). This core affect or "proto-emotion" can give a lot of indications about a person's overall state of mind, so trying to extract that from physiological signals is an enticing prospect. However, it turns out emotions don't come from the heart, but in a very complex way from your brain. This makes the valence dimension of emotion, how pleasant or unpleasant the emotion is, incredibly hard to measure.

Peripheral signals like heart rate or skin conductance (sweat level) aren't directly linked to where emotion originates but are downstream processes of the central nervous system. What we *can measure* peripherally is autonomic tone, where the strongest signals are linked to arousal, how energized an emotion feels, not valence (Kreibig, 2010; Sato, Kochiyama, & Yoshikawa, 2020; Sato & Kochiyama, 2022). The best measure of valence we have comes from electromyography (EMG), which measures the electrical activity of muscle contraction, in this case the face (Sato, et al., 2021). Sounds great, but who wants to work satellite ops all day with electrodes all over your face? You could try and use a camera to watch your face instead, but in many operational environments, filming isn't allowed due to the sensitivity of the missions. Another candidate, electroencephalography (EEG) frontal asymmetry, which measures electrical activity of the brain, has been shown to measure motivation, not valence (Harmon-Jones & Allen, 1998; Harmon-Jones, 2004; Harmon-Jones & Gable, 2018).

By looking at the reality of what physiological signals actually measure, passive valence measurement seemed an increasingly remote possibility. Then, I came across surveys of machine learning (ML) methods that predicted valence and arousal from physiological data, including studies using just peripheral data (Kacimi & Adda, 2025; Saganowski et al., 2022). Digging into that led me to Albraikan et al. (2018), one of the few studies that both restricted itself to peripheral signals and tested cross-subject generalization (aka testing the same model on different people). Unfortunately, the results were lacking in nuance and less than promising. The reported "success" on valence classification is inflated by the task design because of the binary median-split classification. Valence is classified into "high" and "low." Someone slightly above the midpoint gets grouped with someone at the extreme high end, despite being very different states, while getting split apart from someone just barely below the midpoint, despite being nearly identical. Peripheral-only binary valence classification averages ~70% (e.g., Wiem & Lachiri, 2016; Doma & Pirouz, 2020) in the reviewed literature, with random chance of correctness being 50%. But only one of these studies tests whether that performance holds up on unseen people, and its accuracy drops to 65.5%, only about 15 points better than chance, suggesting even the modest 70%+ numbers may not generalize.

None of this rules out physiological monitoring for satellite ops entirely, it just means valence is out of the running. Heart rate variability already has an established track record as an operational biomarker for workload and stress, from aviation cockpits to command-and-control and cyber defense settings (Burlacu et al., 2026). Sleep is even further along: the U.S. Navy has already deployed Oura Rings and similar wearables fleet-wide to monitor sleep-wake patterns during multi-week deployments at sea, with reasonable compliance and minimal interference with duty (Kubala et al., 2024). Neither of these efforts had to solve the valence problem. They both lean on the arousal-adjacent measures that peripheral signals already capture. The best next step for satellite operations is to adapt the work already done to this particular application and save valence for more relevant contexts like clinical mental health monitoring (e.g., Broulidakis et al., 2023) where pleasant-unpleasant discrimination is vital.

As for the original question, though, my dreams of reading your emotions from a smart watch are dashed. Until someone invents a wearable that measures EMG as unobtrusively as a fitness ring, valence can't be measured simply and passively, especially not in a setting where cameras, EEG headbands, and detailed self-report surveys are all off the table. For now, the quest to know the feelings of satellite operators as intimately as Deanna Troi knows a room full of Klingons stays backlogged in the list of side quests.

---

*References*

Albraikan, A., Tobon, D. P., & El Saddik, A. (2018). Toward user-independent emotion recognition using physiological signals. IEEE Sensors Journal, 19(19), 8402–8412.

Broulidakis, M. J., Kiprijanovska, I., Severs, L., Stankoski, S., Gjoreski, M., Mavridou, I., Gjoreski, H., Cox, S., Bradwell, D., Stone, J. M., & Nduka, C. (2023). Optomyography-based sensing of facial expression derived arousal and valence in adults with depression. Frontiers in Psychiatry, 14, 1232433.

Burlacu, A., Brinza, C., Geman, O., Karppa, M., & Hemanth, D. J. (2026). Heart rate variability as a dual-use digital biomarker: Integrating clinical, AI, and operational perspectives on human performance and resilience. BMC Cardiovascular Disorders. DOI: 10.1186/s12872-026-05543-z

Doma, V., & Pirouz, M. (2020). A comparative analysis of machine learning methods for emotion recognition using EEG and peripheral physiological signals. Journal of Big Data, 7, 18.

Harmon-Jones, E., & Allen, J. J. B. (1998). Anger and frontal brain activity: EEG asymmetry consistent with approach motivation despite negative affective valence. Journal of Personality and Social Psychology, 74(5), 1310–1316.

Harmon-Jones, E. (2004). Contributions from research on anger and cognitive dissonance to understanding the motivational functions of asymmetrical frontal brain activity. Biological Psychology, 67, 51–76.

Harmon-Jones, E., & Gable, P. A. (2018). On the role of asymmetric frontal cortical activity in approach and withdrawal motivation: An updated review of the evidence. Psychophysiology, 55(1).

Kacimi, Y., & Adda, M. (2025). Comprehensive review of physiological signal-based emotion recognition: Methods, challenges, and insights on arousal and valence dimensions. Procedia Computer Science.

Kreibig, S. D. (2010). Autonomic nervous system activity in emotion: A review. Biological Psychology, 84, 394–421.

Kubala, A. G., Roma, P. G., Jameson, J. T., Sessoms, P. H., Chinoy, E. D., Rosado, L. R., Viboch, T. B., Schrom, B. J., Rizeq, H. N., Gordy, P. S., Hirsch, D. A., Biggs, A. T., Russell, D. W., & Markwald, R. R. (2024). Advancing a U.S. Navy shipboard infrastructure for sleep monitoring with wearable technology. Applied Ergonomics, 117, 104225.

Russell, J. A. (1980). A circumplex model of affect. Journal of Personality and Social Psychology, 39(6), 1161–1178.

Saganowski, S., Perz, B., Polak, A., & Kazienko, P. (2022). Emotion recognition for everyday life using physiological signals from wearables: A systematic literature review. IEEE Transactions on Affective Computing.

Sato, W., Kochiyama, T., & Yoshikawa, S. (2020). Physiological correlates of subjective emotional valence and arousal dynamics while viewing films. Biological Psychology, 157, 107974.

Sato, W., & Kochiyama, T. (2022). Exploration of emotion dynamics sensing using trapezius EMG and fingertip temperature. Sensors, 22(17), 6553.

Sato, W., Murata, K., Uraoka, Y., Shibata, K., Yoshikawa, S., & Furuta, M. (2021). Emotional valence sensing using a wearable facial EMG device. Scientific Reports, 11, 5757.

Wiem, M. B. H., & Lachiri, Z. (2016). Emotion classification in arousal-valence dimension using discrete emotional physiological signals. International Journal of Advanced Computer Science and Applications, 7(3).