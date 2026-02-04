# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

Multiple critical security vulnerabilities in the Versa Concerto network security and SD-WAN orchestration platform. When chained, these flaws could allow remote attackers to bypass authentication, escape Docker containers, and fully compromise both the application and the underlying host system. 

 The **Outbreak Response - Versa Concerto SD-WAN Authentication Bypass** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.3.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/versa-concerto-authentication-bypass) contains information about the outbreak alert **Outbreak Response - Versa Concerto SD-WAN Authentication Bypass**. 

## Background: 

Versa Concerto is an orchestration and management platform for Versa Networks’ SD-WAN and SASE (Secure Access Service Edge) solutions. Widely deployed in enterprise and managed networking environments.

CVE-2025-34025: Privilege escalation flaw enabling Docker container escape and host-level code execution.

CVE-2025-34026: Traefik authentication bypass allowing unauthorized access to admin endpoints and internal Spring Boot Actuator data. CVE-2025-34026 was flagged for urgent attention and added to the CISA Known Exploited Vulnerabilities Catalog. 

CVE-2025-34027: Traefik authentication bypass leading to arbitrary file writes and full remote code execution via package upload endpoint.

 

## Announced: 

Organizations are advised to apply vendor patches, restrict access to orchestration interfaces, and implement protective controls such as network segmentation and strict administrative access policies to limit exposure. 

## Latest Developments: 

January 29, 2026: FortiGuard Labs released a Threat Signal.
https://www.fortiguard.com/threat-signal-report/6327/versa-concerto-sd-wan-authentication-bypass

January 22, 2026: CVE-2025-34026 was added to the CISA Known Exploited Vulnerabilities Catalog 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|
