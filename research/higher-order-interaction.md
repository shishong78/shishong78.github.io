---
layout: splash
title: "Network Wormholes"
classes: wide
date: 2020-02-11
tags: [social networks, strength of weak ties, twitter data, phone data, network wormholes]
excerpt: "Social Networks, Strength of Long Ties"
mathjax: "true"
---
{::comment}
Can put the following above to create a header image.
header:
  image: "/images/wormholes/singapore_wormholes.png"
{:/comment}


# Higher-Order Social Interactions
<!-- ![Singapore](/images/higher-order-interactions/copresence-tweets.png){:class="img-responsive"}{:height="900px" width="1000px"} -->

{% include figure
   image_path="/images/higher-order-interactions/copresence-tweets.png"
   alt="Co-Present Triads"
   caption="Modeling higher-order relationships from co-mentioned tweets. (Left) Filled triangle: We view a triad engaged in higher-order interaction if each and every member creates at least one tweet in which the other two members are mentioned together. (Middle) Not a closed triangle: B and C do not reciprocate the co-mentioned tweet from A. (Right) Closed but unfilled triangle: Users A and B each co-mention all other members of the group, but C only mentions A and B individually in two separate tweets (C1 and C2). We categorize this triad consisting of three bidirected edges as a closed triangle, but not as a filled triangle with higher-order interaction, since C has not co-mentioned A and B in a tweet. By this operationalization, all filled triangles are closed triangles, but not all closed triangles are filled."
   class="img-responsive"
   width="500"
%}



## Abstract
Higher-order network models have emerged as powerful extensions of the dyad-centric graph representation for modeling complex social systems. However, the combinatorial flexibility they offer necessitates a principled approach to defining higher-order interaction, such as what constitutes "social" interaction in a group context. Lax definitions can substantially distort the description of a domain's social characteristics (e.g., homophily, in-group bias), exaggerate the connectivity of the system, and potentially lead to misguided conclusions about its social dynamics (e.g., diffusion potential). We draw upon microsociological insights to rigorously define higher-order interactions among 38 million Twitter users across six Anglophone countries, modeling the communication networks as simplicial 2-complexes. We find structural effects of higher-order interactions at the dyad to the entire network level that are otherwise untraceable in a graph representation. At the dyad level, edges involved in triadic higher-order interactions exchange messages more frequently than comparable edges embedded in triads comprised of isolated one-on-one interactions. Furthermore, the topological features of these edges are highly predictive of tie strength over and above standard social network correlates. At the triad level, three Twitter users engaged in higher-order interactions tend to express more positive and negative emotion in their tweets than those who engage only in dyadic interactions. The relative frequency of positive emotion words is highest when users in the triad do not engage in any exclusive pairwise interactions. Finally, at the level of the entire network, these higher-order interaction triads are interconnected at surprisingly high levels, suggesting highly integrated social organization.

Article link: [working paper](/assets/docs/Sarker_Park_Higher_Order_Interactions_Twitter.pdf)


<!-- ## Dataset
For this study, I collected 158 million Twitter user accounts between 2013 and 2014 and constructed bidirected @mention networks in eight countries. The edgelists for these eight countries, with @mention frequency as weights, can be found in [Harvard Dataverse](https://doi.org/10.7910/DVN/NPRNCC). -->


