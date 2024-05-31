Coalition Race Simulator

This project is an implementation of the "Coalition Race" simulation, designed to help politicians in SPLand form a coalition.
The simulation uses an object-oriented approach in C++ and emphasizes efficient memory management and the use of C++ features such as the Rule of Five.

Features:
- Robust Simulation: Implements a political coalition formation process using a graph-based model where parties are vertices and collaborations are edges.
- Agents and Policies: Each party is managed by agents with selection policies (Mandates or Edge Weight).
  Agents offer neighboring parties to join their coalition based on these policies.
- Party States: Parties transition through states (Waiting, CollectingOffers, Joined) and decide on coalition offers using join policies (Mandates or Last Offer).
- Multithreading: Handles multiple agents simultaneously to enhance real-time gameplay.
- Configuration and Logging: Customizable settings and detailed logging for game actions and events.
