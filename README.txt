Building Bayesian network using Genie

The assumptions for the given question are listed below

Nodes:

Confirm_Quarantine node:- node to make a decision if an individual needs to be sent to quarantine or not.

Infected node:- Person infected with the virus hypothesis (prior probability).


Assumed Probabilities:

we have assumed P(Infected = True) = 0.2

The Confirm_Quarantine node is based on "Fly in person","Status_health" and "Infected" nodes.

So we have assumed the following:

P(Confirm_Quarantine = true / Infected = true) = 1
P(Confirm_Quarantine = true / Infected = false , Fly_in_person = true , status_health = true) = 0.9
P(Confirm_Quarantine = true / Infected = false , Fly_in_person = true , status_health = false) = 0.6
P(Confirm_Quarantine = true / Infected = false , Fly_in_person = false , status_health = true) = 0.7
P(Confirm_Quarantine = true / Infected = false , Fly_in_person = false , status_health = false) = 0
