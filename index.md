---
layout: default
---

Student: Mu Zhu (mzhu5@ncsu.edu)

Advisor: Munindar P. Singh (mpsingh@ncsu.edu)

Exam time: Novmber 16th, 2021, 10:00am - 12:00pm on [Zoom](https://ncsu.zoom.us/j/97387573498)

## Commitee:
- Munindar P. Singh (Chair)
- Khaled Abdel Harfoush (GSR)
- Jin-Hee Cho (External Member)
- Rudra Dutta
- William Enck


<hr />

### Abstract

Much research has been devoted to defensive deception, as it offers a unique approach to cybersecurity. Unlike traditional security measures, such as firewalls and intrusion detection systems (IDS), defensive deception allows the defender to become involved in the attack process to deceive and misdirect its opponents. This makes it particularly effective in detecting and mitigating stealthy attacks, such as malicious reconnaissance and insider threats. Two main promising directions to develop defensive deception techniques are observed in the literature. First, strategies of an attacker and defender have been commonly modeled based on game-theory where the defender takes deception strategies with the aim of creating confusion for attackers or misleading them so they would choose suboptimal or poor strategies. Second, deception techniques based on machine learning (ML) have been proposed to create realistic fake information or decoy objects that mimic real objects to mislead or lure attackers.
To better understand defensive deception approach, we survey existing research on defensive deception to determine the use of game theory and machine learning, the types of attacks discussed, the defensive deception techniques proposed, and how the authors evaluate their approaches.

Honeyfile systems are a popular defensive technique that is used to detect stealth threats, such as insider attacks. However, they can cause disruption to legitimate users and generate false alarms, leading to confusion for administrators. To address this issue, we have developed a novel honeyfile system called Mee. This system is based on decentralized deployment and centralized control. We have also developed a Bayesian game to model interactions between attackers, defenders, and users to help the defender create an optimal strategy. We have tested Mee in a testbed and evaluated it based on the defender's payoff, the attacker's payoff, and the true/false positive rates when detecting insider threats. The simulation results show that Mee performs better than traditional honeyfile systems and causes less disruption for regular users.
The Mee project is limited in that its game theory model can only be applied to relatively simple scenarios, such as those involving a few players. To enhance honeyfile research, we use Deep Reinforcement Learning (DRL) and a more complex environment (e.g., considering multiple users and attackers simultaneously) to increase its effectiveness. We construct a DRL model and simulated the interaction between legitimate users, insider attackers, and defenders. Our findings demonstrate that HoneyMee can significantly improve the accuracy of insider threat detection and the payoff for the defender.

Another approach investigates a hybrid honeypot system that combines low and high-interaction honeypots to deceive attackers. We propose a two-player hypergame model to determine how the defender should deploy the honeypots to protect the network from malicious reconnaissance. Our model considers the imperfect knowledge of each player about their opponent and examines the payoff between them. We also analyze the best strategies for each player within the hypergame framework.
We investigate an approach to generate honey traffic, which represents fake network flows to defend against malicious reconnaissance (e.g., such as packets sniffer and banner grabbing). This research adopts the Generative Adversarial Network (GAN) architecture, which includes generator and discriminator components. We use the generator to learn the features of network flows that come from actual servers and produce fake flows. In addition, we use the discriminator to mimic an attacker, which needs to distinguish legitimate flows from fake flows. 

<hr />

### Dissertation:
- [Version 1 (Nov. 2rd, 2023)](./dissertations/version1.pdf)

### Slide:
- Coming Soon.
