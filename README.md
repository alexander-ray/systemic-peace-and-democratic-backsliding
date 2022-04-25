# Overview
Small repo to store the code and replication data for the course project in PSCI 7053. The project--titled "Backsliding democratic trajectories and systemic peace"--is a relatively simple numerical simulation-based analysis of the consequences of democratic backsliding on system-level conflict, through the lens of the dyadic democratic peace hypothesis.

We begin with the conceptualization of democratic ``trajectories'' (as coined in [2]) from Gleditsch & Hegre (1997) [1], assessing the original "inverted U" hypothesis with contemporary data. We then assess the role of endogeneity in the democratization-conflict propensity relationship. Finally, we take an initial look at how network structure and position impact variance in the impact of different democracies backsliding.

## Code
This is a pretty linear jupyter notebook, intended for each cell to run one after the other. The version put in this repo uses the various thresholds from the core analysis (e.g. polity threshold of 3 and above to code "democracy"), but these are generally clearly defined variables than can be changed as necessary.

## Data
Data files in this repo are directly drawn from the following sources:
* Correlates of War (CoW) interstate war (v4) [4]
* Polity (v5ish) [3]
* CoW direct contiguity (v3.2) [5]

These are included solely for ease of replication. For new analyses, we recommend sourcing the most up-to-date files from each source individually.

# References
1. Gleditsch, Nils Petter and Håvard Hegre (1997). “Peace and democracy: Three levels of analysis”. In: Journal of Conflict resolution 41.2, pp. 283–310.
2. Kadera, Kelly M, Mark JC Crescenzi, and Megan L Shannon (2003). “Democratic survival, peace, and war in the international system”. In: American Journal of Political Science 47.2, pp. 234–247.
3. Marshall, Monty G. and Ted Robert Gurr (n.d.). Polity5 Project, Political Regime Characteristics and Transitions, 1800-2018. url: http://www.systemicpeace.org/inscrdata.html.
4. Sarkees, Meredith Reid and Frank Wayman (2010). Resort to War: 1816-2007. CQ Press. url: https://correlatesofwar.org/data-sets/COW-war.
5. Stinnett, Douglas M et al. (2002). “The Correlates of War Project Direct Contiguity Data, Version 3.0”. In: Conflict Management and Peace Science 19.2, pp. 59–67. url: https://correlatesofwar.org/data-sets/direct-contiguity.
