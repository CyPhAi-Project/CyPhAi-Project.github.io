---
title: "About CyPhAI"
---

Artificial intelligence (AI) and data sciences are revolutionizing information systems used for control and supervision of various devices (such as sensors, robots, IoT devices) with higher levels of autonomy and adaptability in uncertain and dynamically changing environments. Among such information systems are Cyber-Physical Systems (CPS) from which emerges a new generation of AI-intensive Cyber-Physical Systems (AI-CPS). Autonomous vehicles are examples to illustrate the synergy between CPS and AI. The physical processes in such a system are typically CPS, with vehicle hybrid dynamics, low-level engine control, and a high-level control loop where AI components are present in sensors, cameras, image and scene recognition modules that influence the coordination and decision-making of the system to assure their autonomy. These modules are designed by training AI components (such as neural networks) that learn how to classify road conditions and react to them.

AI-CPS pose a number of design challenges. On one hand, AI techniques are “unpredictable” due to a lack of formal frameworks to provide safety guarantees. On the other hand, the existing CPS design methods, relying on rather fixed models (that is once a system is deployed, its structure and configuration are generally fixed), face a fundamental problem because AI-CPS are supposed to learn from experience and interactions with the environment, adapt and regulate their behaviors accordingly. It is imperative to ensure that their learning-enabled components work correctly because they may directly affect people’s lives and fortune. Self-driving car accidents caused by AI failures are striking real examples. In general, the outcomes of learning activities in AI components are not easily interpretable. When coupling CPS with AI, the increased heterogeneity in dynamics and behaviors can aggravate the reliability and explainability issues, if the learning activities are not properly formalized.

This project, **Formal Analysis and Design of AI-intensive Cyber-Physical Systems – CyphAI**, is a 5.5-year research project that tackles the above-mentioned challenges on AI-CPS. To achieve these objectives, we combine formal methods from computer science with mathematical control theory, and we use several tools from the field of functional analysis, differential equations, optimization, probability and statistics to solve our problems and establish mathematical rigor in our results. In particular, we develop mathematical concepts for measuring and sampling sets of AI-CPS behaviors, with respect to quantitative criteria (such as property satisfaction, control performance). These concepts are necessary for formal reasoning and extracting information from data, to learn hybrid processes and combine black-box (model-free and data-driven) and white box (model-based) approaches for validation, control, and online monitoring.

The project consists of researchers in Japan (funded by JST) and France (funded by ANR). The project is organized in 5 work packages (WPs) below that cover major problems in the design process: 

+ WP1-Learning for CPS,
+ WP2-Learning within CPS,
+ WP3-Validation of CPS and AI-CPS,
+ WP4-Monitoring and Control for Enforcing Dependability and Performance constraints, and
+ WP5-Case Studies, Applications and Tools.
