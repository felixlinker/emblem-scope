# Authenticated digital distinctive emblems and signs

## Background

During armed conflict, medical and certain humanitarian infrastructure enjoys special protection under International Humanitarian Law (IHL) which mandates that such infrastructure must be respected and protected by all parties to the conflict.
IHL defines a number of physical emblems, including the Red Cross, Red Crescent, and Red Crystal, which visually signal protection under IHL for physical assets.
These physical emblems have been adopted and recognized widely in real conflict environments.

Nowadays, conflicts increasingly take place in the digital world and digital assets serving a humanitarian purpose already enjoy protection under IHL.
However, digital assets (as of now) cannot signal protection to those interacting with them by digital means.
We seek to develop a digital emblem that signals protection under IHL using digital means so that medical and humanitarian digital assets can also advertise their protection.
Such a digital emblem would need be accessible through well-known mechanisms, easily recognizable, verifiable, and accountable against misuse to enable good-faith actors to respect it.

Work on marking such a digital emblem should be conducted in close collaboration with all relevant legal guardians of the in-scope IHL emblems so that all results can actually be used for their intended purpose.

## Goals

The working group seeks to develop a mechanism that:

- can signal that a digital asset enjoys protection under IHL using network interfaces (so that targets using network communication can also present emblems through network communication);
- parties to a conflict are willing to use (for example, verifying a digital emblem should not identify the verifier).

## Non-Goals

* Technical protections against cyberattack
  * Distinctive emblems and signs are protective because of IHL and the respect of those symbols. The group will not consider work on defining mechanisms to directly protect against cyberattack.

* Deconfliction
  * Notification or identification of physical resources or locations of people or resources to protect from physical attacks are accomplished through other methods, including physical emblems and deconfliction lines. This group will not design systems for labeling physical assets or indicating protection against physical or kinetic attack, only digital attacks (where there may be a physical and digital form for the same asset).

## Program of work

1. Define the requirements for authenticating, distributing, and the digital distinctive emblems and signs under IHL for network endpoints and resources. Requirements will include:
    - authenticatable by multiple, decentralized sources;
    - inspectable without identifying the inspector as a potential threat actor;
    - extendable and removable;
    - accountable for misuse;
    - resilient and implementable, including in times of conflict.

2. Develop a protocol for authenticating and verifying emblems attached to or indicated for network endpoints and resources.

3. Develop protocol extensions for distributing and communicating emblems through existing networking transports that are determined to meet the requirements from Section 1. Work with existing WGs that own the selected transport protocols.

4. Describe any additional needs for developing, deploying, and monitoring a system in practice, including in times of conflict.
