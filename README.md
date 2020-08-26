# Process-Engineering-Template
This workbook is a collection of some of the stuff I've done over the last couple of years in my degree chemical engineering degree and moments of boredom. Particularly I've tried to include a variety of the Macros I’ve created because from my experience this is something we were not exposed to at university. Please feel free to use this work but do not redistribute without linking to this repository.

If you have any suggestions or make any of your own improvements to this workbook please share them here. I've given a brief outline of each of the sheets below but if you've had a play with the workbook and want to talk about it further feel free to reach out.

Enjoy,

Riley O'Donnell

## MBEB
A mass and energy balance is far easier to complete around the streams of a PFD drawing however needs to be presented in a stream table. On a small PFD it is relatively easy to link all the cells up manually however quickly it becomes a tedious task. This sheet uses a macro to automate this process and proved a lifesaver in my design project when I was being given last minute revisions to the PFD.
Inputs are included on the left with a range and reference. If you’re keen you can create a similar sensitivity analysis to that which is included on the Economics sheet to quantify the impact of uncertainties.

## Economics
I never got the opportunity in any of my engineering courses to dive as deep into the project economics as I would have liked but this sheet just has a few useful tools that have been very helpful in analysing project viability.

The Sheet is based off an inputs sheet that has all the relevant economic data and the outputs from the MBEB. This enables scenario analysis and a Monte Carlo to be conducted on the economics. The cashflow table dynamically formats based on the project life simplifying the effort in presenting different scenarios. A macro script runs a Correlated Monte Carlo Analysis using the matrices from the Monte Inputs sheet that outlines the correlations between the inputs and produces an output in the form of binned distributions for effective communication of the results.

## Project Gantt Chart
Just a simple project timeline with critical path dependencies. It is also just a useful sheet for allocating resources and hours in a project. I've used this in a finance competition to add project delay timeline effects to the economic scenario analysis (although not included in this example). It was important to develop this tool to ensure the project structure was maintained as the various stage completion time was varied in a scenario analysis. This enabled me to quantity the effects of timeline changes and then to explore where a trade-off on cost of development vs time of development was valuable. 
