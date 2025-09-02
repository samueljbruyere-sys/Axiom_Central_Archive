# Reconnaissance Briefing: The Compute Exchange Front

## Executive Summary

This briefing confirms the core tenets of [[The Compute Exchange Doctrine]]. The battlespace for decentralized, peer-to-peer compute is not theoretical; it is an active and rapidly developing front. Multiple assets, primarily from the [[Bazaar]], are already deployed and operational. The Commander's hypothesis is validated: while network latency remains a significant bottleneck for real-time, low-latency _inference_, the architecture for massively parallel, asynchronous, distributed _training_ is not only viable but is already being executed in the wild.

## Asset Classification

The assets in this new theater can be classified by their primary mission objective:

1. **Distributed Training Networks:** These systems focus on aggregating compute from multiple peers to train or fine-tune AI models. Their success is measured in total computational throughput over time.
    
2. **Distributed Inference Networks:** These systems focus on running a single, pre-trained model across a network of peers to serve user requests. Their success is measured in latency and uptime.
    

## Key Deployed Assets

### 1. [[Bittensor]] (The Sovereign Market)

- **Asset Designation:** The most mature and operationally significant asset in this theater.
    
- **Tactical Analysis:** [[Bittensor]] is not a single project but a protocol for creating a decentralized, blockchain-incentivized market for artificial intelligence. Operators connect their hardware to the network, offering their computational resources to various "subnets," each dedicated to a specific task (e.g., text generation, image generation, data analysis). The network rewards operators with its native cryptocurrency (TAO) based on the value they contribute. This is a direct, functional prototype of a "Compute Exchange." It is actively being used for both distributed training and inference.
    
- **Doctrinal Fit:** It is the ultimate expression of the [[Bazaar]], creating a free market for compute that directly challenges the [[Cathedral]]'s centralized control.
    

### 2. Petals (The Cooperative Swarm)

- **Asset Designation:** A university-led research project focused specifically on distributed _inference_.
    
- **Tactical Analysis:** Petals is a direct answer to the question of running massive, 100B+ parameter models without a supercomputer. It operates like [[BitTorrent]]. A large model is broken into smaller layers, and each peer in the network holds a few of these layers. When a user makes a request, the request "torrents" through the network, being processed sequentially by the peers holding the necessary layers.
    
- **Doctrinal Fit:** This confirms your hypothesis regarding network speed. While functional, Petals is significantly slower than running a model on a dedicated server. It proves that collaborative inference is _possible_, but it is currently too slow for most real-time applications.
    

### 3. Federated Learning (The [[Cathedral]]'s Approach)

- **Asset Designation:** A more controlled, privacy-focused doctrine for distributed training, primarily pioneered by [[Google]].
    
- **Tactical Analysis:** In Federated Learning, the model is sent out to the data, not the other way around. For example, a model for improving a phone's keyboard predictions is sent to millions of individual phones. Each phone fine-tunes the model on the user's private typing data, and then only the small, updated model parameters (the "learning") are sent back to the central server to be aggregated.
    
- **Doctrinal Fit:** This is the [[Cathedral]]'s attempt to co-opt the doctrine of decentralized training while maintaining centralized control. It validates the technical viability of the approach but rejects the open, permissionless ethos of the [[Bazaar]].
    

## Conclusion: Hypothesis Confirmed

Your assessment is correct. The networks are not yet fast enough for low-latency, peer-to-peer LLM _inference_ to compete with centralized servers.

However, for distributed _training_—a task that is asynchronous and massively parallel—the foundation is not just there; it is operational. The "torrent for compute" model is viable, and assets like [[Bittensor]] are already executing this doctrine in the field. The Compute Exchange is online.

o7