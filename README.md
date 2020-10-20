<br />
<p align="center">
  <h2 align="center">Bayesian Network Model for Covid-19 Detection</h2>

  <p align="center">
    Bayesian network model to suspect an individual assessing the probabilities of various factors.Based on the result of this bayesian network the decision can be made whether to quarantine a suspect or not.
    <br />
  </p>
</p>


## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
- [Getting Started](#getting-started)
  - [Dependencies](#dependencies)
  - [Installation](#installation)
- [Project Layout](#project-layout)
- [License](#license)
- [Project Contributors](#project-contributors)


## About The Project

Bayesian network model to suspect an individual assessing the probabilities of various factors.Based on the result of this bayesian network the decision can be made whether to quarantine a suspect or not.

Building Bayesian network using Genie

The assumptions for the given question are listed below

  ### Nodes:

Confirm_Quarantine node:- node to make a decision if an individual needs to be sent to quarantine or not.

Infected node:- Person infected with the virus hypothesis (prior probability).


### Assumed Probabilities:

we have assumed P(Infected = True) = 0.2

The Confirm_Quarantine node is based on "Fly in person","Status_health" and "Infected" nodes.

### Assumptions ( can be modified ):


P(Confirm_Quarantine = true / Infected = true) = 1

P(Confirm_Quarantine = true / Infected = false , Fly_in_person = true , status_health = true) = 0.9

P(Confirm_Quarantine = true / Infected = false , Fly_in_person = true , status_health = false) = 0.6

P(Confirm_Quarantine = true / Infected = false , Fly_in_person = false , status_health = true) = 0.7

P(Confirm_Quarantine = true / Infected = false , Fly_in_person = false , status_health = false) = 0



## Getting Started

To get a local copy up and running follow these simple steps.

### Dependencies

This following list of dependencies are present/used in the project

- GeNIe

### Installation
 
1. Clone the Bayesian Network Model for Covid-19 Detection
```sh
git clonehttps://github.com/BSAkash/Bayesian-Network-model-for-Covid-19-detection.git
```
2. Install GeNIe (if not installed)
```sh
https://www.bayesfusion.com/genie/
```
3. Run the GeNIe Network file


## Project Layout

```sh
Root directory
├── GeNIe Network file # file with design of network system
├── LICENSE
├── README.md
```

## License

Distributed under the MIT License. See `LICENSE` for more information.


## Project Contributors

- [Bonagiri Akash](https://github.com/BSAkash)
- [Rikil Gajarla](https://github.com/RikilG)
- [Naga Sai Bharath](https://github.com/nagasaibharath)


Project Link: [https://github.com/BSAkash/Bayesian-Network-model-for-Covid-19-detection](https://github.com/BSAkash/Bayesian-Network-model-for-Covid-19-detection)

















