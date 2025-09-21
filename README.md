# Spiking Scallop — A Neuromorphic Model for Directional Sensing & Response

**Author:** Adam Gottesman • **Institution:** Imperial College London

This repository hosts the final PDF describing **Spiking Scallop**, an interactive neuromorphic system that mimics directional sensing and motor-like responses using networks of configurable **leaky integrate-and-fire (LIF)** neuron PCBs. It’s built primarily as an **educational installation** that makes neural dynamics tangible and visual. :contentReference[oaicite:0]{index=0}

## File
- [`spiking-scallop.pdf`](spiking-scallop.pdf) — complete report with model, equations, module diagrams, and implementation notes. :contentReference[oaicite:1]{index=1}

## What it is (in one minute)
- **Neuron PCBs** implement LIF neurons with tunable parameters (e.g., \(V_{\text{leak}}\), \(\tau_{\text{mem}}\), synaptic weights, excitatory/inhibitory selection). :contentReference[oaicite:2]{index=2}  
- Each **sensory module** (“eye”) couples a **bio-latch** (mutually inhibiting neurons) with a **Winner-Take-All (WTA)** network for **directional dominance**. :contentReference[oaicite:3]{index=3}  
- When multiple eyes are activated together, latch↔WTA **coupling** produces **central pattern generators (CPGs)**—rhythmic activity emerging from the network. :contentReference[oaicite:4]{index=4}  
- The system is deployed as a large **1.7 m × 1.7 m** interactive wall with LEDs that visualize membrane voltages and spikes. :contentReference[oaicite:5]{index=5}

## Key concepts (from the paper)
- **LIF dynamics:** \( \tau_{\text{mem}}\,\frac{dV}{dt}=-(V - V_{\text{leak}})+R_m I(t)+\sum S_{\text{sign}} W \) with threshold/reset spiking. :contentReference[oaicite:6]{index=6}  
- **Bio-latch:** state can persist after stimulus via structured mutual inhibition; transitions define “default ↔ reactive” behavior. :contentReference[oaicite:7]{index=7}  
- **WTA network:** enforces directional selection across eyes; inhibition across modules ensures a single winner. :contentReference[oaicite:8]{index=8}  
- **CPGs:** joint latch–WTA state-space coupling yields self-sustained oscillations reminiscent of biological pattern generators. :contentReference[oaicite:9]{index=9}

## Educational goals
- Provide a **hands-on, visual** demo of neuromorphic principles (integration, thresholding, inhibition, competition).  
- Let learners **tune parameters** (leak, weights, time constants) and **see** behavior change in real time. :contentReference[oaicite:10]{index=10}

## How to cite
> Gottesman, A. *Spiking Scallop: A Neuromorphic Model for Directional Sensing and Response in Biological Systems.* Imperial College London, 2025. :contentReference[oaicite:11]{index=11}

## Keywords
neuromorphic hardware, LIF neurons, winner-take-all, bio-latch, central pattern generators, interactive installation. :contentReference[oaicite:12]{index=12}
