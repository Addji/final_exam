---
layout: default
---

Student: Mu Zhu (mzhu5@ncsu.edu)

Advisor: Munindar P. Singh (mpsingh@ncsu.edu)

Exam time: Novmber 16th, 2021, 10:00am - 12:00pm on Zoom

## Commitee:
- Munindar P. Singh (Chair)
- Khaled Abdel Harfoush (GSR)
- Jin-Hee Cho (External Member)
- Rudra Dutta
- William Enck


<hr />

### Abstract

Defensive deception attracts much attention from research communities. Unlike traditional cybersecurity techniques, such as firewall and intrusion detection systems (IDS), defensive deception lets the defender participate in attack processes to lure and mislead the opponents' perspective. Therefore, defensive deception shows effectiveness when detecting or mitigating stealthy attacks, such as malicious reconnaissance and insider threats.

To better understand how defensive deception works, we first investigate different deception techniques and analyze their advantages and disadvantages. We survey current game theory (GT) and machine learning (ML) based defensive deception research to identify (1) what GT and ML are used, (2) what kinds of attack are discussed, (3) what defensive deception technique is proposed, and (4) how the authors evaluate their schemes.

As a popular defensive deception technique, honeyfile systems are commonly used to detect stealth threats, such as insider attacks. Although deployed honeyfiles can help uncover attackers, they can disrupt the work of legitimate users and generate false alarms, which may confuse administrators. To fill this gap, we propose a novel honeyfile system, named Mee, that relies on decentralized deployment and centralized control. 
In recent work, we have developed the Mee structure to model interactions between the attacker, the defender, and the users with a Bayesian game to assist the defender in producing an optimal strategy. 
We implement Mee in the testbed and evaluate it by considering 1) the defender payoff, 2) attackers payoff, and 3) true/false positive rate when detecting insider threats. The simulation results show that Mee has better performance than the traditional honeyfile system and disturbs regular users less.

In our first proposed work, we will expand the above research to use deep reinforcement learning (DRL) and adopt a more complicated environment (e.g., multiple users and attackers involved) to increase the realization.
Our research objective is to increase the effectiveness of honeyfile and reduce false positive alarms from regular users.

In our second proposed work, we will investigate an approach to generate honey traffic, which represents fake network flows to defend against malicious reconnaissance (e.g., such as packets sniffer and banner grabbing). This research adopts the Generative Adversarial Network (GAN) architecture, which includes generator and discriminator components. We use the generator to learn the features of network flows that come from actual servers and produce fake flows. In addition, we use the discriminator to mimic an attacker, which needs to distinguish legitimate flows from fake flows. 

Overall, this dissertation seeks to improve defensive deception by investigating reliable and practical designs.

<hr />

### Dissertation:
- [Version 1 (Aug 6 th, 2021)](./oral_proposal/first_version.pdf)

### Slide:
- Coming Soon.
