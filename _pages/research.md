---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

 I am interested in delineating the mechanisms underlying the developmental trajectories of cognition and mental health, as well as investigating external and internal factors that influence these trajectories, including but not limited to environmental factors, maternal depression, and sex hormones. I am also interested in all things fMRI and have spent multiple years in an fMRI analysis lab, and the work I completed there is very much the backbone of my research today. 

## Functional MRI Connectivity Analyses (2021-2023)
During my time in [Dr. Peter Bandettini's lab](https://fim.nimh.nih.gov/), I worked on a multitude of projects analyzing [functional connectivity in resting-state fMRI](https://fim.nimh.nih.gov/projects/bold-connectivity-dynamics) and how to leverage connectivity information to enhance brain-behavior predictions.  The goal of my first project was to investigate the source of individual variability in resting-state fMRI in healthy adults. We hypothesized that a potential source of variability during rest is 'ongoing cognition' that subjects engage in over the course of the scan ([a](https://www.pnas.org/doi/abs/10.1073/pnas.1501242112), [b](https://www.jneurosci.org/content/41/6/1130.abstract)). Ongoing cognition refers to everything from thinking about what to make for dinner to stressing about an upcoming meeting with your boss to daydreaming about a vacation and more. We used a [publicly available dataset](https://www.nature.com/articles/sdata2018307) that consisted of multiple resting-state scans per subject as well as responses to a post-scan questionnaire that asked subjects to characterize their in-scanner experience. We found significant associations between distinct patterns of thought and functional connectivity patterns, highlighting the potential need to account for these effects when examining resting-state fMRI data. Stay tuned for our publication!

Next, I sought to investigate how to leverage connectivity information to boost brain-behavior predictions. I employed a new technique to compute ['edge time series'](https://www.nature.com/articles/s41593-020-00719-y) from traditional ROI time series to capture the co-fluctuation between any given pair of nodes at each point in time across the whole scan. Then, to summarize these co-fluctuations overtime, we computed multiple summary metrics, including time-insensitive metrics, such as mean, and time-sensitive metrics, such as autocorrelation and dynamic entropy, to form new ROIxROI matrices for each subject and evaluated their predictive ability. We found that mean co-fluctuation, i.e. static functional connectivity, proves to be the best predictor of cognitive traits using [this dataset](https://www.frontiersin.org/articles/10.3389/fnins.2012.00152/full), so far! Stay tuned for this publication, as well. 

You can find more information about my research in the [Poster Presentations](poster-presentations.md) and [Publications](publications.md) tabs.

<style>
    body {
        color: black;
        background-color: #DFF7FF;
        font-family: serif;
    }
    h1 {
        color: black;
        background-color: #DFF7FF;
        font-family: serif;
    }
    h2 {
        color: black;
        background-color: #DFF7FF;
        font-family: serif;
    }

</style>