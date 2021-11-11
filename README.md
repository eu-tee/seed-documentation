# Overview

Security Suite for Engineering Endpoint Devices (SEED) is a Mobile Device Management (MDM) platform for the Government Commercial Cloud (GCC) 2.0 environment.  

It includes the following components:

- **TechPass**: An [Identity Service] that allows single sign-on for users to seamlessly access Singapore Tech Stack and GCC 2.0 services.

- **Cloudflare Teams**:  This ensures Zero trust network access and includes Cloudflare Access and Cloudflare Gateway.

  **Cloudflare Access**  
	- securely exposes internal applications and services
	- enforces device-aware user access policies
	- logs application activities

  **Cloudflare Gateway**
  - secure Domain Name Server (DNS) resolver
  - filters malicious content
  - inspects and logs all DNS queries
  - allows requests based on granular policies

**Development Environment Endpoint Posture**: The device management layer of MDM. It manages the following:

- **Microsoft Intune**: Provides device and application management, including remote application deployment and selective device wipe.

- **Microsoft Defender Advanced Threat Prevention (MDATP)**: Enterprise class vulnerability management, threat detection and response security solution.

- **Tanium**: Endpoint assets and posture management. Works with Cloudflare to ensure posture based conditional access.
