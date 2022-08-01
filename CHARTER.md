# Debug, Trace, and Performance Monitoring Special Interest Group Charter

RISC-V needs open standards for the RVI ecosystem to develop SoCs. The Debug, Trace, and Performance Monitoring Special Interest Group (DTPM SIG) shall define the strategy for creating a suite of open standards for SoC debug, trace, and performance-monitoring infrastructure capabilities in a RISC-V SOC.

The goal for the DTPM SIG shall be to define a strategy to establish specifications and guidelines for the interfaces, transports, and other pieces of the SoC infrastructure for DTPM such that IPs developed for the RISC-V ecosystem can all work together in an SoC without (or with little) customization to integrate.

SoC need common capabilities such as standard programming interfaces, standard transports, security frameworks, external and internal interfaces, etc. for debug, trace, performance-monitoring capabilities. Continuous improvement in the state of the art requires a strategy for identifying the technology development roadmap for extending existing specifications to address new requirements. A strategy is required to prioritize the gaps and the technology development roadmap.

The DTPM SIG shall focus on the following areas:

* Standard programming interface 
  * Standard register sets and/or a model for them to help the software tooling ecosystem and foster greater interoperability for trace, scan interface, SoC performance monitoring, NoC monitors, analytics, remote telemetry, etc. 
  * Unified discovery of capabilities
  * Comprehend internal (e.g., in integrated IPs) and external (e.g., on the interface to the SoC) interfaces as well as NoCs/Interconnects, etc. between the IPs.
* Standard transports
  * Protocols and formats for debug/trace/performance-monitoring encapsulation 
  * Secure transport of trace, crash logs, remote debug, debug authorization, commands, extraction of status/state, analytics, remote telemetry, etc.
* Unified security architecture
  * Authorization and access control for SoC DTPM. 
  * Classification of capabilities into categories and ability to authorize each category by itself (e.g., silicon creator, system integrator, end user, RMA, etc.)
  * Reporting state of debug or debug authorization in the SoC security posture - attestations, data sealing. Ability to opt-out of debug on each boot.
* Cables and connectors
  * Provide guidelines and recommendations on the use of connectors, cables, ports, etc. and other external interfaces to debug tools such as hardware probes, etc.
* Debug, Trace, and SoC performance monitoring features
  * Identify strategy for improving and/or enhancing the existing standards such as the debug specification, and trace specifications. For example, cycle accurate trace, possible extensions to support the vector extension, etc.
  * The DTPM SIG shall oversee and coordinate maintenance of standards related to Debug, Trace and SoC performance monitoring for RISC-V by recommending and putting in place the appropriate enabling mechanisms and structures.
* Evangelizing and enabling
  * Put in place strategies to disseminate information about the RISC-V standards as related to DTPM SIG.
  * Reach out to co-travelers and ecosystem partners such as tools and IP developers to enable wide adoption of the RISC-V standards and promote interoperability between IPs in the RISC-V ecosystem.
  * Develop tutorials and other collateral to support this effort.
  * Support and promote academic research in this domain.
  * Open: Would interop events or other interop “tooling” or assistance be done?  Would this be something under the purview of the SIG?

The DTPM SIG shall work on a gap analysis by starting with a review lay of the land on RVI debug, trace, SoC performance-monitoring capabilities - what exists, what's happening, what's missing, and strategy to address the gaps - with focus on high priority gaps that need to be addressed for building RISC-V based SoCs. The SIG shall work on creating and/or adopting common language and terminologies for the DTPM domain. Where appropriate the SIG shall identify the need for, define the strategy for, and oversee efforts - by recommending formation of targeted TGs or fast-track extensions - to define additional collateral to support this vision. This may include reference implementation, reference models, integration guides, or other aids. The goal of the DTPM SIG shall be to avoid reinventing the wheel and to adopt as-is or extend if required existing specifications. Prioritization is important so that we focus our scant resources on the areas that are most valuable to the member companies.
