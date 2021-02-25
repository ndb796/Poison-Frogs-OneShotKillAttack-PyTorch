## <b>One-Shot Kill Poison Attack</b>

> Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks

### (Source Codes) PyTorch Implementation: One-Shot Kill Poison Attack

1. [One Shot Kill Poison Attack: Targeted Clean-Label Poisoning Attacks <b>(ResNet)</b>](%5BOne_Shot_Kill_Poison_Attack%5D_Poison_Frogs_Targeted_Clean_Label_Poisoning_Attacks_(AlexNet).ipynb)
2. [One Shot Kill Poison Attack: Targeted Clean-Label Poisoning Attacks <b>(AlexNet)</b>](%5BOne_Shot_Kill_Poison_Attack%5D_Poison_Frogs_Targeted_Clean_Label_Poisoning_Attacks_(ResNet).ipynb)

### How does this attack work?

<img width="80%" src="https://user-images.githubusercontent.com/16822641/109210717-8f011000-77f0-11eb-8b5f-53cf98736f49.png"/>

### How to generate poison image?

<img width="70%" src="https://user-images.githubusercontent.com/16822641/109210734-96c0b480-77f0-11eb-8a72-bc84925d292d.png"/>

* We assume transfer learning in which the victim model utilizes a pre-trained model as a fixed feature extractor.
* In this transfer learning situation, the One-Shot Kill Poison Attack shows high attack success rate.

### References

* Poison Frogs! Targeted Clean-Label Poisoning Attacks on Neural Networks, <b>[NIPS 2018](https://arxiv.org/abs/1804.00792)</b>
