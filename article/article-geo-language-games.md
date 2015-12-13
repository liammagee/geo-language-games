% Geo-Language Games: An Agent-Based Model of the Role of Terrain in Language Diversity
% Rachel Hendery, Liam Magee

# Geo-Language Games
> It is not the case that, for example, Jawoyn country is called that because it is or was occupied by people who speak the Jawoyn language. Rather, it is called Jawoyn country because it is the region in which that language was directly installed or 'planted' in the landscape by Nabilil 'Crocodile', a Dreamtime creator figure who moved up the Katherine River, establishing sites and leaving names for them in the Jawoyn language (Merlan and Rumsey 1982). In this formulation, language and country are directly linked, and the mediated link is between language and people: Jawoyn people are Jawoyn not because they speak Jawoyn, but because they are linked to places to which the Jawoyn language is also linked.

> Rumsey 1993:200

> [...]

> [I]n the Aboriginal myths which associate language and land, no account at all is taken of people, or peoples. Languages, or even mixtures of them, are directly placed in the landscape by the founding acts of Dreamtime heroes. From that point on, the relation between language and territory is a necessary rather than a contingent one.

> Rumsey 1993:204

<!--- note: I'd rather find a quote from an Aboriginal person directly, rather than from a white anthropologist, but this can be a placeholder til I find something better. At least Alan writes well. -->

## Introduction



## Language located in the landscape
<!--- something about Aboriginal conceptions of language and space; linguistic models disconnected with landscape -->

## Agent-based modelling and language

% brief survey of existing agent-based models of language. Highlight how they largely ignore geography

<!--- have copied in the following couple of paragraphs from our DH abstract. They'll need some revision if we end up using them. I haven't formatted the references or added them to a bib file yet either. -->

Agent-based models assume one or more computer-based autonomous, linguistic, reactive, proactive and intentional agents who interact with each other and their environment (Wooldridge and Jennings 1995; Gilbert and Troitzsch 2005). Given an initial set of states distributed across a group of agents, and a finite set of rules, these interactions can then show interesting emergent patterns over time (Axelrod 1997). As both Axelrod (1997) and Epstein (2008) argue, agent-based models can be useful as much for their explanatory as for their predictive value – as sorts of “thought experiments” (Axelrod 1997, p.4) for elucidating how complex phenomena might emerge from simple assumptions. Increasingly, ABMs have been applied to social phenomena such as economic systems (Farmer and Foley 2009), political cooperation and decision-making (Axelrod 1997), urban development (Batty 2007), social networks (Macy and Willer 2002) – and language change (Steels 1997). 

However, agent-based modelling remains an underexplored – if tantalising – approach to understanding models of language change. As one example, Parkvall et al (2013) proposed an agent-based model for the evolution of creoles in which agents follow extremely simple rules about talking to each other and updating their lexicon to ‘learn’ new words from each other during interactions. They tested this model for various combinations of founder languages, and found that it successfully predicts the lexifier language in the resulting creole. 

The idea behind such a simulation is not to include all possible factors in language change, but to pare them down to the minimum needed to get a realistic outcome. This shows us which elements are most important in language change. Elements that have been considered in previous agent-based simulation of language change include social networks (Troutman et al 2008), genetic predisposition of the agents to language learning (Baronchelli et al 2012), and diversity of founding population (Parkvall et al 2013), but to our knowledge, no one has included geographical factors.


## Our model / our software
<!--- I don't know how much detail we want to go into here. Just an outline of how it can work? Or an example of a model and what we gain from it? -->

<!--- Again, have copy-pastaed relevant paras from our abstract -->
We build upon existing work with a web-based ABM framework, Fierce Planet (Magee 2012; Magee 2014). The affordance of this framework over more established ABM frameworks such as NetLogo, Repast and CORMAS (e.g. Bajracharya and Duboz 2013) is the relative accessibility of simulations – these can be easily deployed and shared with other researchers and communities. We adapt that framework for three-dimensional rendering using WebGL and Three.js, and import geographical models for both locations. For Papua New Guinea, we import DEM models developed by USGS. For Palmerston Island we construct a DEM model using World Machine since it is too small and low-lying to be picked up satellite. 

Both height and foliage act as cost-based constraints on the movement of members of different tribal groups. As a general rule, this constrains interactions between groups, while reinforcing bonding ties within groups. Our model shows that, given a common linguistic origin, over time geographical constraints acts as a factor in the gradual divergence of dialect and language between two groups. This is especially so when one or both groups are exposed to exogenous influences. We also model a range of alternative scenarios, where connections between groups become easier or more difficult due to alterative pathways between them. 



## Conclusions


### Sample images

![Sample image](images/fp1.png)


### Sample Citations

 - [@hendery2015palmerston]
 - [@hurford1989biological]
 - [@kirby1998fitness]
 - [@kirby2014iterated]
 - [@livingstone1999modelling]
 - [@nowak2002computational]
 - [@parkvall2013simulating]
 - [@tesar1998iterative]


## References
