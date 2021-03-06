---
title: "Benefits of dynamic network models"
categories:
  - Needs Review
  - Dynamic Network Models
---

Traditional user equilibrium highway assignment models predict the effects of congestion and the routing changes of traffic as a result of that congestion. They neglect, however, many of the details of real-world traffic operations, such as queuing, shock waves, and signalization. Such operational details are important both to reflect reality and to evaluate policies associated with improving traffic operations. Examples of such policies might include ramp metering, signal co-ordination, or targeted improvements at choke points.

Currently, it is common practice to feed the results of user equilibrium traffic assignments into dynamic network models as a mechanism for evaluating these policies. The simulation models themselves, however, do not predict the routing of traffic, and therefore are unable to account for re-routing owing to changes in congestion levels or policy, and can be inconsistent with the routes determined by the assignment. Dynamic network models overcome this dichotomy by combining a time-dependent shortest path algorithm with some type of simulation (often meso or macroscopic) of link travel times and delay. In doing so it allows added reality and consistency in the assignment step, as well as the ability to evaluate policies designed to improve traffic operations.

The nonlinear and chaotic nature of congestion at the micro scale and its effect on vehicular flow characteristics is well documented (May 1990; Newell 1995; Boyles et al. 2008). The benefits of modeling individual vehicle interactions and how they collectively give rise to level of service and congestion have long been captured in traffic simulation models. Such models have traditionally been tractable for small study areas, owing to their data requirements and heavy computational demands. Other than a few isolated attempts to simulate large networks, such models were not considered practical at the urban or metropolitan level irrespective of what benefits they might have offered. TRANSIMS arguably changed that, demonstrating proof of concept from its inaugural case study in Dallas–Fort Worth to early deployments today.

During the same time frame that TRANSIMS has evolved, separate progress has been made in the use of DTA models in planning studies, an application not widely anticipated a decade ago. Given their successes and the growing interest in fusing activity-based travel demand models with dynamic network models it is likely that such models will become more widely used in practice over the coming decade. As with activity-based models in general, practitioners are eager to learn what practical advantages such models have over traditional static traffic assignment models. Currently, there is insufficient evidence to conclusively show their superiority. Regardless of the level of network resolution, such models have already provided indispensable benefits that cannot be obtained using traditional static network models:

-   Dynamic network models are capable of capturing the time-dependent effects of congestion, something that static models are not capable of doing. The incidence, location, and duration of congestion, often evidenced as bottlenecks in the roadway system, lead to highly unstable flows, high variabilities in travel times, and unreliable system states. These effects can only be represented in an aggregate sense—in both time and space—in macroscopic models, which assume invariant flows and travel times over the entire analysis period. Even when modeling peak periods the variability in travel times and their effect on departure time, mode, [destination](Destination_Choice_Models), and route choice varies considerably within that time. Static models are simply unresponsive to such variation, and to the extent that they can approximate the macroscopic outcomes, do so in a manner inconsistent with cur-rent traffic flow theory.

<!-- -->

-   Macroscopic models represent traffic control in an abstract manner, such that improvements in that realm go unnoticed. Traffic signals are the most abundant control strategy in place at the present time, although areawide control schemes, ITS, and traveler information systems are rapidly increasing in importance. With management and operation of the transportation system playing an ever-increasingly important role, the need for tools appropriately sensitive to such actions is critical. Dynamic network models fill this gap.

<!-- -->

-   Dynamic tolling and congestion pricing schemes rely heavily on accurate and detailed in-formation about temporal patterns of demand and their response to changes in levels of service. To the extent that such schemes become more commonplace in the future investors in and operators of such systems will require more robust estimates of network performance and response than can be obtained from static models. Dynamic network models are ideally suited for such analyses.

<!-- -->

-   Global climate change is renewing the focus on mobile source emissions. California has adopted statewide policies to dramatically reduce mobile source emissions (California Air Resources Board 2009). The recent proposed federal “cap and trade” legislation includes regulatory powers for the EPA over emissions estimation methods and standards. These changes will require more accurate estimation of link and network travel times, which in turn will require a more robust representation of the time-dependent effects of congestion and traffic control systems. By contrast, most static models resort to using post-processing of macroscopic assignment results to derive credible estimates of link travel times.

It is expected that the various types of dynamic network models will converge at some point. Some commercial packages offer the capability to seamlessly move between varying levels of detail and, depending on the flow levels, between different models (macroscopic, mesoscopic, and microscopic). If DTA models fulfill expectations, it is possible they will be capable of providing most of the performance measures required, and at an acceptable level of resolution and accuracy, without resort to traffic simulation models.

Source
------

[NCHRP Synthesis 406: Advanced Practices in Travel Forecasting - A Synthesis of Highway Practice](NCHRP_Synthesis_406_Advanced_Practices_in_Travel_Forecasting__A_Synthesis_of_Highway_Practice)



