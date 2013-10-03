---
published: true
layout: post
tags: 
  - engineering
  - relief device
  - ranting
  - technical
category: techincal
comments: true
---

I have worked with relief system for a while and usually when it comes to external fire scenarios, there is a curse. API 521 is about the only source of guidance provided to determine if an external fire scenario does apply. However, the wording is sometimes open ended and not very helpful. 


## What Really Grinds My Gear

Some word of wisdom regarding external fire from API 521 Section 5.15.2.1:

> API 521 [...] It is typically assumed that the vessel is isolated during a fire in order to simplify the analysis, although a more detailed analysis can be warranted in certain cases. Crediting for alternative relief paths that remain open during an overpressure event is generally an acceptable practice. [...] It can be difficult to establish with a degree of certainty whether a particular line will indeed remain open under all fire conditions. [..] Ultimately, the user shall decide whether a scenario is credible or not.

*Source: American Petroleum Institute, API RP 521. Guide for Pressure-Relieving and Depressuring Systems. 2008*

Wonderful, this is what really grinds my gear:

> What kind of guidance tell me it's up to me?

![what really grinds my gear](http://www.themobilityresource.com/wp-content/uploads/2013/05/grinds-my-gears.jpg)

## Here Comes the "Intepretations"

Such open ended guidance "it's up to the user" gives lot of room for intepretation. Sometimes engineer can take advatage of it. 

## It Starts Slowly
To start, the only creterion needed to consider external fire is:

1. Equipment contains liquid

Often, the fire scenarios relief rate would be too much for the valves or cause other problems (high inlet/outlet pressure drops). We further scrutinize the scenarios. We agreed (with the client) on additional criteria:

1. Equipment is within 25 ft elevation. 
2. Platform must be able to sustain a pool of liquid (grading and sloped ground to a drain cannot sustain a pool of liquid).
3. Only consider the shell side of a shell and tube exchanger (ignore the tube side).
4. Only consider external fire for shell and tube exchangers if the shell side could be automatically blocked in. (Per plant's procedure, exchangers are drained if manual valves are closed to isolate the exchanger).
5. On the other hand, consider external fire if the exchanger shells that can be automatically isolated with automatic control valves/pumps at the inlet or outlet during operation. 

## Then It Gets Worse
The criteria above are well within reasonable intepretation of API 521. However, we ventured into some arguable criteria:

1. If exchangers shell can be automatically isolated with an automatic control valve, the control valve/pumps must be within the same fire zone. 

    The reasoning is that the control valve/pump will stay open during an operational fire, allowing heated liquid to carry heat from the fire away and avoid overpressure.

    One can argue that it's unclear how plant shutdown may or may not isolate the exchanger with these automatic control valves. The exchanger can indeed be isolated because of the fire even though the valve is not directly impacted by the fire. 

2. Only consider external fire if there are nearby equipment that contains hydrocarbon. Ignore all process line. 
    
    The reasoning is that leaking in process line will give minimal amount of hydrocarbon instead of a pool of liquid. 
    
    Arguably, a process line can be a supply of hydrocarbon. Leaving it long enough, you'll get a pool of flammable liquid. 

3. Is there an ignition source?

    Often we would look at plot plans, and we found ourselves limit the fire source to "electrical" equipment such as "pumps, compressors, motors..." To verify and argue that there is nothing that can ignite hydrocarbon is difficult.

4. Can the hydrocarbon be ignited? 

    For example, kerosene or diesel has a higher ignition temperature, you must heat them up before they can ignite.

5. What is the required flow of this hydrocarbon to sustain a fire long and large enough to boil the liquid inside? Can that much hydrocarbon be provided?
	
    The reasoning is that a small leak will not generate enough heat to boil a large vessel of liquid to cause overpressure.

    Okay, you have say, this one is a bit crazy. 
    
## It's Gotta stop
When things for open to intepretation, it does not favor to the engineer. Engineering judgement is a wrestle between costs and safety. And when being faced with these hypothetical questions (would it happen? how would it happen? is it likely?), it is best to conduct a study to know what's the probability is. Sadly, that also costs money. 

Does anyone else have this problem or it's just me?

Curses!