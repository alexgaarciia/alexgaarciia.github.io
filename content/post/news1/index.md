---
title: We’re Heading to ONDM 2024!
summary: Our research paper has been accepted for presentation at the 2024 International Conference on Optical Network Design and Modeling (ONDM)
date: 2024-05-01
authors:
  - admin
# tags:
#   - Hugo Blox
#   - Markdown
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---

I'm excited to share that my first research paper — where I am a first author — has been accepted for presentation at the 2024 International Conference on Optical Network Design and Modeling (ONDM). 

The paper introduces a reinforcement learning approach for routing in packet-optical networks using hybrid telemetry metrics.

### TL;DR

In this work, we present a reinforcement learning-based approach to optimize routing in packet-optical networks. The algorithm learns to select the best paths by dynamically adapting to real-time measurements collected from both the optical and packet layers, such as pre-FEC bit error rate, propagation delay, and link load.

By combining these metrics into a latency-based reward system, our Q-learning agent can make routing decisions that respond to current network conditions, even when those conditions degrade. We evaluate the algorithm on two topologies, a small 8-node setup and the Tokyo Metropolitan Area Network, showing how it adapts routes based on changes in link quality.

### Links to paper and code

You can find both the paper and the code open to the research community:

📄 **Paper**: [Reinforcement-Learning based routing for packet-optical networks with hybrid telemetry](https://arxiv.org/abs/2406.12602)

💻 **Code repository**: [PacketOpticalLatencyRL](https://github.com/alexgaarciia/PacketOpticalLatencyRL) on GitHub

