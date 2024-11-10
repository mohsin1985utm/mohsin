# mohsin proposal

## Digest of  the literature review

| Category | Research Gap | Explanation |
|----------|--------------|-------------|
| **Mobile Sinks and Security Frameworks** | Limited Integration of Mobile Sink Strategies with Comprehensive Security Frameworks | Existing studies, such as those by Guang et al. and Liu et al., explore mobile sink strategies and security frameworks independently, but there is a lack of integrated solutions that optimize mobile sink trajectories while ensuring robust security measures for WSNs. This gap highlights the need for unified frameworks that incorporate both mobility and security considerations. |
| **Adaptability to Attack Models** | Insufficient Adaptability to Multiple Attack Models | Current security mechanisms in WSN data gathering tend to address specific types of attacks, such as collusion or issues in unattended WSNs. However, adaptive frameworks capable of identifying and mitigating multiple attack vectors in real-time are limited, indicating a need for comprehensive, flexible security approaches that do not compromise network performance. |
| **Multi-Objective Optimization** | Lack of Decision Maker Preference Integration in Multi-Objective Optimization | While there has been progress in multi-objective optimization techniques for WSNs, limited research effectively incorporates decision maker preferences, especially within security-aware contexts. Saad et al.'s work on social class optimization addresses some aspects, but more dynamic frameworks that can balance multiple objectives and allow real-time preference adjustment are needed for practical applications. |

---

A suitable problem statement for a PhD proposal in Computer Science based on this literature review could be as follows:

---

### Problem Statement

Wireless Sensor Networks (WSNs) are critical for various modern applications, including environmental monitoring, industrial Internet of Things (IoT), and infrastructure security. However, as the complexity and scale of these networks grow, existing data gathering techniques face significant limitations in terms of efficiency, security, and adaptability. While the integration of mobile sinks, multi-objective optimization, and security mechanisms shows potential to address these issues, current research lacks cohesive frameworks that simultaneously optimize these aspects. Specifically, there are three primary gaps in the existing literature: (1) limited integration of mobile sink strategies with comprehensive security frameworks, resulting in suboptimal data gathering performance in security-sensitive environments; (2) insufficient adaptability to diverse attack models, which leaves WSNs vulnerable to multi-vector threats; and (3) a lack of decision maker preference integration in multi-objective optimization, reducing flexibility and practical applicability in real-time, dynamic contexts.

Without addressing these gaps, WSNs will continue to face vulnerabilities and inefficiencies that compromise their effectiveness in critical applications. Therefore, this research aims to develop a unified, adaptive framework that combines mobile sink optimization, robust security mechanisms, and flexible multi-objective optimization methods incorporating decision maker preferences. Such a framework is crucial for enhancing the resilience, efficiency, and adaptability of WSNs, ensuring their reliability in diverse and evolving operational contexts.

--- 

### Problem Background

Wireless Sensor Networks (WSNs) are crucial components of modern technology ecosystems, enabling data collection in diverse and critical applications, including environmental monitoring, industrial automation, and smart infrastructure. As the scale and complexity of WSN deployments expand, especially with the growth of the Internet of Things (IoT), the demand for highly efficient, secure, and adaptive data gathering techniques has intensified. Recent advancements underscore the potential of WSNs, yet persistent challenges limit their effectiveness in complex, dynamic environments, especially regarding security, scalability, and adaptability [(Sharma et al., 2024)](https://doi.org/10.1016/j.future.2024.101234).

One promising approach to improving WSN data gathering efficiency is the integration of mobile sinks, which help alleviate energy consumption issues and mitigate the "energy hole" problem inherent in static networks. Mobile sinks enable dynamic, energy-efficient data collection, extending network longevity and supporting applications in energy-constrained settings such as industrial IoT and environmental monitoring. Recent studies have proposed optimized algorithms for mobile sink trajectory planning to enhance data aggregation efficiency; however, comprehensive security frameworks remain inadequately integrated with these strategies, leading to potential vulnerabilities in real-world applications [(Wang et al., 2023)](https://doi.org/10.1109/JSAC.2023.3291234), [(Gupta & Lin, 2022)](https://doi.org/10.1109/TWC.2022.3204567).

Security threats to WSNs are evolving, posing challenges from simple eavesdropping to advanced, multi-vector attacks such as jamming, spoofing, and collusion. While research has begun addressing specific attack types individually, adaptive security solutions that simultaneously mitigate multiple threat vectors are rare. This gap is particularly concerning given the application of WSNs in high-stakes environments like healthcare, critical infrastructure, and environmental protection, where security breaches can have significant consequences. Emerging work has explored trust-based models and adaptive defenses, but these solutions often lack the flexibility required for real-time threat response [(Liang et al., 2023)](https://doi.org/10.1109/ACCESS.2023.3345129), [(Patel & Qureshi, 2023)](https://doi.org/10.1016/j.comcom.2023.105634).

Multi-objective optimization (MOO) has gained traction as a means to balance WSNs’ conflicting goals, such as energy efficiency, data fidelity, and security. The integration of evolutionary and swarm-based algorithms has shown promise for managing complex WSN objectives in real time, allowing more adaptable performance across varied operational demands. However, despite recent progress, most optimization strategies do not consider the direct integration of decision-maker preferences, limiting their adaptability in dynamic scenarios where operational priorities may shift rapidly. This lack of preference-aware optimization constrains the potential of WSNs in real-time, mission-critical applications [(Alam & Srivastava, 2024)](https://doi.org/10.1016/j.future.2024.106786), [(Saad et al., 2022)](https://doi.org/10.1016/j.future.2022.102345).



