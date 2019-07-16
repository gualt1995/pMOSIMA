
# pMOSIMA
Trust and reputation model for open multi-agent systems
## Introduction

This project aims at building a model of trust and reputation in the context of an open multi agent system.

There are two types of agents in the system, providers and customers, the customers have the ability to interact with the providers, when they do so they need to pick the best provider they can reach, this selection uses the following components to evaluate the trustworthiness of a provider.

 - **Interaction trust** : trust based on your previous interaction with the agent
 - **Witness Reputation** : the agent tries to get the opinion from other customers that interacted with the potential provider
 - **Certified Reputation** : the customer asks the provider ,certificates from their previous interaction with other customers
 - **Role Based Trust** : trust based on the status of the provider

Combining these four components should allow a customer to have a decent estimation of the trust level for a any given agent. the full description of the model (FIRE) can be found in the following paper : *An integrated trust and reputation model for open multi-agent systems (Trung Dong Huynh, Nicholas R. Jennings, Nigel R. Shadbolt). [DOI 10.1007/s10458-005-6825-4]*

  

To implement this model we used a language called Netlogo, specialized in multi-agent environment modeling, The descriptions of the algorithms used to implement the different components can be found in the full report for this project :  MOSIMA.pdf (french only)

  
  

## Usage :

open model.nolgo3d in Netlogo, you can the play the simulation in the interface tab.
 
<p align="center">
<img src="https://raw.githubusercontent.com/gualt1995/pMOSIMA/master/screen_1.png" height="300" title="">
<img src="https://raw.githubusercontent.com/gualt1995/pMOSIMA/master/screen_2.png" height="300" title="">
</p>
  
  

## Original project by :

[Gualtiero Mottola](https://github.com/gualt1995)<br>

[Alexandre Bontems](https://github.com/schonwetter)<br>
