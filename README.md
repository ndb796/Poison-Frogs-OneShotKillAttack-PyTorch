## <b>One-Shot Kill Poison Attack</b>

> Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks

* This repository provides simple PyTorch implementations for a <b>One-Shot Kill Attack</b> method.
* This repository shows attack success rates that are similar to the success rates in the original paper.
* If you have questions about this repository, please send an e-mail to me (dongbinna@postech.ac.kr) or make an issue.

### (Source Codes) PyTorch implementation: One-Shot Kill Poison Attack

1. [One-Shot Kill Poison Attack: Targeted Clean-Label Poisoning Attacks <b>(ResNet)</b>](%5BOne_Shot_Kill_Poison_Attack%5D_Poison_Frogs_Targeted_Clean_Label_Poisoning_Attacks_(AlexNet).ipynb)
2. [One-Shot Kill Poison Attack: Targeted Clean-Label Poisoning Attacks <b>(AlexNet)</b>](%5BOne_Shot_Kill_Poison_Attack%5D_Poison_Frogs_Targeted_Clean_Label_Poisoning_Attacks_(ResNet).ipynb)

### How does this attack work?

<img width="80%" src="https://user-images.githubusercontent.com/16822641/109384310-4b60f000-792f-11eb-967e-1406e435c704.png"/>

### How to generate a poison image?

<img width="70%" src="https://user-images.githubusercontent.com/16822641/109210734-96c0b480-77f0-11eb-8a72-bc84925d292d.png"/>

* We assume a transfer learning scenario in which the victim model utilizes a pre-trained model as a fixed feature extractor.
* In this transfer learning scenario, the One-Shot Kill Poison Attack shows a high attack success rate.

### References

* Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks, <b>[NIPS 2018](https://arxiv.org/abs/1804.00792)</b>
