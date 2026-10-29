# Awesome-Role-Based-Access-Control-RBAC

## Top Role-Based Access Control (RBAC) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Identity Governance, Fine-Grained Authorization & Privileged Access Management*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Role-Based Access Control (RBAC)** and the broader Identity and Access Management (IAM) landscape. These tools enable organizations to define roles, assign permissions, enforce least privilege, and govern who can access what—across employees, contractors, services, and AI agents.



**Examples** include Shopify Staff Accounts, Okta, Microsoft Entra ID, Ping Identity, JumpCloud, OneLogin, CyberArk, BeyondTrust, SailPoint, and Rippling Identity (the category leaders).



**Open-source emphasis**: RBAC is a domain where open-source tooling is **mature and production-proven across distinct layers**. **Keycloak** and **WSO2 Identity Server** provide full IAM with RBAC, SSO, and federation . For fine-grained authorization, **Permify**, **SpiceDB**, and **Cerbos** implement Zanzibar-inspired or policy-as-code models that go beyond simple RBAC . For privileged access, **JumpServer** provides a mature PAM platform . Identity governance is served by **midPoint** from Evolveum, recognized as a leading open-source IGA product . No single open-source project replicates the full SaaS suite of Okta or SailPoint, but these tools cover the core needs well.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Shopify Staff Accounts](https://help.shopify.com/en/manual/your-account/staff-accounts)**  

  Native staff permission system within Shopify admin; assign roles and granular permissions to control access to orders, products, customers, analytics, and settings.



- **[Okta](https://www.okta.com/)**  

  Leading identity cloud platform with Universal Directory, SSO, MFA, lifecycle management, and role-based access policies for workforce and customer identities.



- **[Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/microsoft-entra)**  

  Microsoft's cloud identity service (formerly Azure AD) with role-based access control, conditional access, Privileged Identity Management (PIM), and integration across Microsoft 365 and Azure.



- **[Ping Identity](https://www.pingidentity.com/)**  

  Enterprise identity platform with SSO, MFA, directory, and API access control for workforce and customer use cases.



- **[JumpCloud](https://jumpcloud.com/)**  

  Cloud directory platform with SSO, device management, LDAP, RADIUS, and role-based access for hybrid workforces.



- **[OneLogin](https://www.onelogin.com/)**  

  Identity and access management platform with SSO, MFA, and user provisioning (now part of One Identity).



- **[CyberArk](https://www.cyberark.com/)**  

  Privileged access management leader with vaulting, session isolation, and least-privilege controls for privileged accounts and credentials.



- **[BeyondTrust](https://www.beyondtrust.com/)**  

  Privileged access management and remote access security platform with password safe, session management, and least-privilege enforcement.



- **[SailPoint](https://www.sailpoint.com/)**  

  Identity governance and administration (IGA) leader with access certification, role mining, and lifecycle management for compliance.



- **[Rippling Identity](https://www.rippling.com/)**  

  Identity and access management within Rippling's unified HR/IT platform; automates onboarding/offboarding and enforces role-based access across connected apps.



## Open-Source GitHub Projects



### Full IAM Platforms with RBAC



- **[Keycloak](https://github.com/keycloak/keycloak)**  

  The most widely adopted open-source Identity and Access Management platform (Apache 2.0); provides SSO, OAuth 2.0, OIDC, SAML, LDAP, and **RBAC with fine-grained authorization** . Supports user federation, identity brokering, and multi-tenancy. **The default choice for self-hosted IAM** in enterprises and development teams.



- **[WSO2 Identity Server](https://github.com/wso2/product-is)**  

  Open-source IAM (Apache 2.0) verified as a Digital Public Good; supports OAuth2, OIDC, SAML, SCIM 2.0, FIDO2, and **role-based access control** . Manages over 1 billion identities across 1,500+ commercial deployments. **Enterprise-grade** with adaptive MFA and identity federation.



- **[ZITADEL](https://github.com/zitadel/zitadel)**  

  Cloud-native IAM platform built on event sourcing and CQRS for a strong audit trail; supports OIDC, OAuth 2.0, passwordless, MFA, and **RBAC** . **Strong for auditability** and modern cloud-native deployments.



- **[Casdoor](https://github.com/casdoor/casdoor)**  

  UI-first centralized authentication/SSO platform with OAuth 2.0, OIDC, SAML, and **RBAC** . **Developer-friendly** with a clean interface for smaller teams.



- **[Hanzo IAM](https://github.com/hanzoai/iam)**  

  Open-source AI-first IAM with web UI supporting OAuth 2.1, OIDC, SAML, CAS, LDAP, SCIM, WebAuthn, MFA, and **RBAC with fine-grained permissions** . Includes MCP/A2A gateway for AI agents. **Notable for AI agent access control**.



### Fine-Grained Authorization (ReBAC/ABAC/PBAC)



- **[Permify](https://github.com/Permify/permify)**  

  Open-source fine-grained authorization service (Apache 2.0) inspired by Google Zanzibar . Supports **RBAC, ReBAC, and ABAC** via a domain-specific language; responds to access checks in tens of milliseconds; multi-tenant by default. **Acquired by FusionAuth** (2026) but community edition remains open and self-hosted.



- **[SpiceDB](https://github.com/authzed/spicedb)**  

  Open-source Zanzibar-inspired permissions database (Apache 2.0) for fine-grained authorization . The reference open-source implementation of Google's Zanzibar paper; client libraries for Go, Node.js, Python, JVM, and Ruby.



- **[Cerbos](https://github.com/cerbos/cerbos)**  

  Open-core, language-agnostic authorization platform that externalizes **policy-as-code** decisions . Decouples access control from application code; supports RBAC and ABAC with context-aware policies.



- **[Athenz](https://github.com/AthenZ/athenz)**  

  Open-source platform (Apache 2.0) for X.509 certificate-based service authentication and **fine-grained role-based access control** . Designed for dynamic infrastructure (Kubernetes, OpenStack, public cloud); supports centralized management and decentralized enforcement.



### Privileged Access Management (PAM)



- **[JumpServer](https://github.com/jumpserver/jumpserver)**  

  The leading open-source Privileged Access Management (PAM) platform (GPLv3) . Provides on-demand, secure access to SSH, RDP, Kubernetes, Database, and RemoteApp endpoints through a web browser. **The open-source standard for PAM**—a direct alternative to CyberArk and BeyondTrust for teams wanting self-hosted privileged access control.



### Identity Governance & Administration (IGA)



- **[midPoint (Evolveum)](https://github.com/Evolveum/midpoint)**  

  Leading open-source Identity Governance and Administration (IGA) platform (Apache 2.0) developed in Europe . Provides identity lifecycle management, **role mining**, access certification, provisioning (SCIM 2.0), and governance aligned with NIS2, GDPR, and CER. Gartner reviewers note it is a "leading open-source IGA product" with wide integrations, though it requires expertise for deployment . **The strongest open-source IGA option** for organizations needing SailPoint-equivalent governance without commercial licensing.



### Additional Strong Open-Source Options



- **Nubus** — Modular open-source IAM for organizations (AGPL-3.0); central web portal for user management, SSO, roles, permissions, and self-service; supports Kubernetes, on-premises, and hybrid deployments . **European public-sector focused** with prebuilt integrations.

- **Authelia** — Lightweight SSO and MFA portal for web apps; integrates with reverse proxies for access control . **Simpler than Keycloak** for teams needing just SSO + MFA.

- **Logto** — IAM infrastructure with AuthN, AuthZ, MFA, SSO, and multi-tenancy; supports OAuth 2.0, OIDC, and SAML . **Developer-friendly** for modern web apps.



**Frameworks for building custom systems**: Choose by layer. For **full IAM with RBAC and SSO**: Keycloak or WSO2 Identity Server. For **fine-grained authorization beyond RBAC**: Permify or SpiceDB (Zanzibar-style) or Cerbos (policy-as-code). For **privileged access**: JumpServer. For **identity governance**: midPoint. For **AI agent access control**: Hanzo IAM. No single open-source project covers all layers—organizations typically combine a full IAM platform (Keycloak) with a fine-grained authorization service (Permify) and governance (midPoint) based on needs.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- RBAC and IAM platforms handling identity and access data must comply with applicable privacy regulations (GDPR, CCPA) and security frameworks (SOC 2, ISO 27001); **misconfigured access controls can create significant security and compliance exposure**.

- **Open-source RBAC/IAM is mature and production-proven across layers**—Keycloak and WSO2 cover full IAM, Permify/SpiceDB cover fine-grained authorization, JumpServer covers PAM, and midPoint covers IGA. However, no single project matches the integrated SaaS experience of Okta or SailPoint; organizations should select components based on their specific governance, authorization, and privileged access requirements.

- Verify license terms for commercial use; Keycloak uses Apache 2.0, Permify uses Apache 2.0 , JumpServer uses GPLv3 , and midPoint uses Apache 2.0 .



---



**Made for identity architects, security engineers, IAM administrators, and access governance teams.**  

Let's make role-based access control more open, granular, and auditable.
