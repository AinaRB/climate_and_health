---
permalink: /chap1_adaptation/
title: "Adaptation"
author_profile: false
header:
  overlay_image: /assets/images/buildings_bw.jpg
excerpt: "Temporal trends in the temperature health burden"
sidebar:
  nav: "docs"
---

[Page under construction] 

# Taking the temperature of our cities: A story from Sao Paulo, Brazil
*The work discussed below is and adaptation from our work published in the Journal of Urban Health. Refer to the paper for more information or contact the corresponding author.* 

Cite as:
Roca-Barceló, A., Fecht, D., Pirani, M. et al. Trends in Temperature-associated Mortality in São Paulo (Brazil) between 2000 and 2018: an Example of Disparities in Adaptation to Cold and Heat. J Urban Health (2022). https://doi.org/10.1007/s11524-022-00695-7


## Why do we care about temperature?
### A bit of background
Humans are homeotherms species. This means that for the correct functioning of our body, we need our body temperature to be within a certain range regardless of the temperature outside. For humans, this temperature is within a degree or two of 37⁰C(98.6F). If this temperature is not met, our survival is compromised.

The question is, how do we do that? And the answer that evolution has provided us with is thermoregulation. It is a physiologic mechanism which allows our body to internally modulate its temperature. It comprises several processes that are activated when our body temperature diverts too much from the optimal one. Sweating, for example, is one such process. When our temperature increases, our body starts sweating, a form of evapotranspiration, which allows us to expel heat from the body. When our body temperature drops too much, on the other hand, we start shivering, which produces localized heat, slightly raising our body temperature. But as you can imagine, and have probably experienced several times, these processes are not enough when the deviations from the optimal temperature are too large. In those situations, external factors start playing a role. According to Hondulas and colleagues, these external or non-physiological elements can be classified in *behavioural*, *technological* or *infrastructural* depending on whether the adaption occurs thanks to changes in the behaviour patterns, technological advances, or infrastructure, respectively. In most cases, it is a combination of all the factors. 

### What do we mean by adaptation?
The examples we discussed above, depict acute responses to outdoor temperatures. But what about long term shifts in temperature? Say you grew up in Bahamas and you are moving to Helsinki, Finland. Will your body react the same way as that of someone living in Helsinki all their live? Probably your gut feeling tells you that the answer is no. And you are right. We know from several studies that people develop mechanisms that are turned to the usual temperatures they are exposed to. Which makes total sense, right? If I live in a cold place, my metabolism, behaviours, and the infrastructure I have access to, will be tuned to the needs of that specific place. I will not, for example, walk around in a swimsuit (behaviours), nor have the air conditioning on (infrastructure) and my body will for sure, not be sweating (physiological). But this is not only the case when we move country. The same happens if it is not us who move but the environment around us that changes? This is exactly what climate change is. Temperature and weather patterns have changed and will continue to change due to climate change. Not only that but our societies are constantly changing and evolving; new technology is developed, awareness about the risks and prevention options increase, access to infrastructure and facilities changes, and so on. As we have seen above, all this shape our response to temperature of our environment. This is what we call adaptation.

**Adaptation.** *The process of adjustment to actual or expected climate and its effects. In human systems, adaptation seeks to moderate or avoid harm or exploit beneficial opportunities. In some natural systems, human intervention may facilitate adjustment to expected climate and its effects* 

### What happens when these mechanisms fail?
This stress can lead to a wide range of health consequences. The images below summarize some of the main health consequences of both extreme heat and cold and their main clinical manifestations. These effects are more acute and can happen earlier in people who have a lower capacity of adaptation. This can include people with a compromised thermoregulation mechanism such as the eldest, people with diabetes or babies; people with no access to the right infrastructure or technological adaptations such as people at risk of poverty, outdoor physical workers… So, it is important to pay closer attention to such groups.
   
Source: CDC


## Why is this important?
To protect the population, we need to know what temperatures are of risk and which population groups are at higher risk. Finally, as we have seen above, these patterns are likely to change over time as temperatures change and the underlying factors for adaptation also change. Hence, we also need to consider the dynamic nature of the association over time. This information is essential to feed in public health policies and interventions such as **Early Warning Systems (EWS)**. These are comprehensive systems that combine weather forecast information with epidemiological evidence to define when to act, who to direct the actions primarily and what actions to take. Basically, when temperatures reach values above said value, an action plan is activated. Multiple thresholds may exist to capture different levels of risk, associated to action plans of increasing magnitude and urgency. As you can imagine, the way these interventions are defined and the temperature at which they are activated is specific to each setting and population. However, regardless of the exact intervention there are two pieces of information that are essential. 

*At what temperature do we activate these interventions?*

*Who are they addressed to primarily?*

To answer these two questions, we need to model the association between temperature and mortality risk for the setting of interest. Not only that but we need to make sure that what we capture represents the most up to date reality for that population. Epidemiological studies investigating how these association changes over time and by population group is vital. And this is exactly what we did.

## Our study
### What did we do?
We collected data on all deaths occurred between 2000 and 2018 in the municipality of Sao Paulo and daily mean temperature. We then calculated the mortality risk associated to the whole temperature spectrum for each year and measured whether there was any clear trend over time. We did this for all population and focusing on different vulnerable populations, namely by age, gender, and ethnicity.

### Sao Paulo
Located in the south-east of Brazil, near the Atlantic coast (see the image below), it is one of the seven megacities in the world, with over 11M inhabitants. Its population is expected to raise in the next years and so is temperature. Therefore, providing the right up to date information to inform public health intervention has the potential of saving a lot of lives.


### Measuring adaptation 
**Non-linear and lagged effects**. Temperature does not have a linear effect on mortality. If you think about it this makes sense. We have just described how our bodies are adapted to the usual weather of the area we live in. Hence, we would expect that changes in the temperature that range are not associated to high mortality, because we are well-adapted. However, as temperatures differ, we would expect the mortality risk to go up. And that is exactly what happens. This translates into a U-shape or V-shape risk curve where the lowest point is within the usual temperature range of the area, and it is known and minimum mortality temperature (MMT) as it registers the minimum mortality rate. The image blow shows this type of shape between temperature (x axis) and the mortality risk (y axis).

In addition, a key thing to consider here is that temperature does not have an immediate impact on us but instead, we see that the effects can be delayed for several days for heat and up to two weeks for cold. This means that when we look at the mortality rate associated to the temperature registered at a given day, we need to consider several days after in our count. in statistics, this is what we called delayed effects. 

A statistical framework that enables us to model both delayed and non-linear effects is the *distributed lag non-linear model* framework developed by Gasparrini et al. 


**Annual specific estimates**. Luckily enough, this framework allows us to model annual associations by simply adding an interaction term in the formula between temperature and time. In this way, we can model the risk associated to each year and explore if it has changed or not. 
The indicators. To monitor changes, we need to pick some indicators. In this study, we have selected changes in the MMT and changes in the risk associated to a given extreme temperature. The image below shows two time periods and early one (yellow) and a later one (purple). On the left hand-side, we see that the risk (y axis) associated to a given temperature (x axis) has decreased in period 2 with respects to period 1. This would suggest that this population has decreased the risk of death when exposed to extreme heat (right of MMT) and cold (left of MMT), indicating adaptation. On the right-hand side, we see that the MMT has shifted to the right, that is, it has increased, suggesting that this population is now better adapted to higher temperatures. 


image

## What did we find?
Note that all visualizations are interactive. You can zoom in and out and select different variables to be plotted by clicking on them. 

### Describing the data
**Meteorological data**. Below you can explore the temperature distribution for each year in the study period in an interactive way. Select the years you want to plot and compare their distribution. You will see that there the distributions seem to flatten in later years shifting from one unique peak to two. This suggests that there are more days with high and low temperatures in later years than early years. However, the changes are not substantial. We can observe the same if we plot it using a slightly different visualization (boxplot).

Plot and animation histogram temperatureHere you can see the daily mean values for daily mean temperature, relative humidity, and air pollution (only large particles, PM10). The last two variables were included in the model to ensure that the relationships that we found were related to temperature only and not affected by the presence of other co-occurring factors.

<center><iframe 
src="https://AinaRB.github.io/climate_and_health/assets/images/adapt/histo_temp.html" height="800" width="1200" frameBorder="0"></iframe></center>

**Mortality data**. The plot below shows daily death counts per population subgroup. Things to note are the clear seasonality and the long-term trends specially for some population groups. Both were included in the model to make sure they didn’t interfere our results.

### Adaptation patterns
There were 3 main findings. We will explore them in detail below:
**The temperature-mortality association changes over time confirming the presence of adaptation and/or maladaptation.** 
The temperature-mortality relationship in Sao Paulo varied significantly over time, confirming the dynamic nature of this association. The plots below show the cumulaive relative risk curves for each year. We can see that the risk varies every year. The tendency for all population is for the risk to extreme heat and for the minimum mortlaity temperature to increase, suggesting that population is overall more used to a higher value of temperature but responds more poorly to increases on this.
 
Figure. Annual cumulative relative risk (cRR) associated to temperature for all non-external causes of deaths, color-coded by year. Interactive plot with select/deselect variables and zoom features enabled. 


**There are disparities in the presence and magnitude of adaptation by population groups**
There exist disparities in the presence and magnitude of adaptation across population groups. The heat-related mortality risk went up for most groups except for males (better adapted). The cold-related mortality risk barely changed for most groups except females who seem to adapt better (decrease) 

Figure. Annual cumulative relative risk (cRR) associated to extreme heat (red) and extreme cold (blue) for (a–s) all non-external causes of deaths by age, sex, ethnic groups, and combination of those. The 95% CI are shown shaded in the same colour. Interactive plot with select/deselect variables and zoom features enabled. 


**Non-climatic factors have a relevant role in adaptation**
The changes observed seemed to be only partially coupled to changes in temperature, suggesting the presence of non-climatic adaptation drivers (e.g., use of AC, change in lifestyle and quality of live, job market shift to larger tertiary sector…)


## Cite our work:
Roca-Barceló, A., Fecht, D., Pirani, M. et al. Trends in Temperature-associated Mortality in São Paulo (Brazil) between 2000 and 2018: an Example of Disparities in Adaptation to Cold and Heat. J Urban Health (2022). https://doi.org/10.1007/s11524-022-00695-7
