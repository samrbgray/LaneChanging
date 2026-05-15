This project provides a dataset and analysis of an Autonomous Vehicle (AV) lane changing experiment

## Pages
- [Dataset](data.md)
- [Methods](methods.md)
- [Results](results.md)
- [Publications](publications.md)
- [Team](team.md)

2.1 Hero / Title Block

Dataset full name: NC-tALC: NCSU Transitional Autonomous Vehicle Lane Changing Dataset
One-sentence tagline: "A real-world, high-resolution dataset capturing lane-changing
behavior of Tesla FSD and ACC-equipped vehicles on a North Carolina collector road."
Two CTA buttons: [Explore the Data] → dataset.html | [Read the Paper] → ArXiv link

2.2 Autonomous Vehicles — Capabilities & Importance
Draft text:

Autonomous and semi-autonomous vehicles are rapidly entering the public roadway
network. Systems such as Tesla Full Self-Driving (FSD) and Adaptive Cruise Control
(ACC) represent the forefront of consumer-available partial automation. Understanding
how these transitional autonomous vehicles (tAVs) behave in mixed-traffic
environments — alongside human-driven vehicles — is essential for safe and efficient
transportation planning.

2.3 SAE Level Classification
Draft text:

The Society of Automotive Engineers (SAE) defines six levels of driving automation
(Level 0–5). tAVs occupy Levels 2 and 3: they can control both steering and
acceleration/braking under certain conditions but still require human supervision
and intervention. As of 2024, approximately 5 million Tesla vehicles are on the
road globally, with roughly 500,000 equipped with FSD capability — making tAVs a
significant and growing share of the vehicle fleet.

Suggest pairing with a simple SAE level graphic (can be created or linked).
2.4 Research Challenges
Draft text:

Lane changing is one of the most complex driving maneuvers: it is a multi-agent
interaction requiring real-time decision-making, gap acceptance, and coordination
with surrounding vehicles. When a tAV performs a lane change, its behavior can
differ meaningfully from human drivers — creating new interaction patterns, safety
considerations, and traffic flow implications that are not yet well understood.
There is a critical need for empirical, naturalistic data to study these dynamics.

2.5 About This Dataset (brief)
Draft text:

The NC-tALC dataset provides 152 controlled lane-changing trials (72 LC +
80 Responding) collected on Sunset Lake Road in Apex, North Carolina. Each trial
includes high-precision RTK-GPS trajectory data at 20 Hz, forward-facing video,
CAN bus signals, and energy consumption data. Two experiment types are included:
one where a tAV acts as the lane changer, and one where tAVs act as the
responding follower vehicles. Both ACC and FSD driving modes are represented.

