# Awesome-Identity-Verification-Two-Factor-Authentication

# Awesome-Identity-Verification-Two-Factor-Authentication

## Top Identity Verification & Two-Factor Authentication Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Identity Verification (IDV/KYC), Multi-Factor Authentication (MFA/2FA), Authenticator Apps, Passkeys & Secure Access*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Identity Verification & Two-Factor Authentication**. These tools cover identity proofing (document + biometric verification), multi-factor authentication, authenticator apps, hardware keys, passkeys/WebAuthn, and enterprise access security.



**Examples** include Zoho Verify, Duo Security, Okta Verify, Microsoft Authenticator, Ping Identity, Yubico, Authy (Twilio), Trulioo, Persona, and Onfido (the category leaders).



**Open-source emphasis**: MFA, OTP, WebAuthn, and identity platforms have a strong open-source ecosystem (privacyIDEA, Keycloak, Authentik, Authelia, FreeOTP, Aegis, and more). Full commercial-grade IDV/KYC remains mostly SaaS, but open building blocks for authentication and self-sovereign identity are plentiful. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Zoho Verify](https://www.zoho.com/verify/)**  

  Zoho’s multi-factor authentication and verification solution for securing accounts and applications with OTP and related factors.



- **[Duo Security (Cisco)](https://duo.com/)**  

  Leading MFA platform with push, OTP, hardware tokens, adaptive policies, and strong device trust features for enterprises.



- **[Okta Verify](https://www.okta.com/)**  

  Okta’s authenticator and MFA solution integrated into the broader Okta Identity Cloud for workforce and customer identity.



- **[Microsoft Authenticator](https://www.microsoft.com/en-us/security/mobile-authenticator-app)**  

  Microsoft’s authenticator app and MFA capabilities tightly integrated with Entra ID (Azure AD) and Microsoft 365.



- **[Ping Identity](https://www.pingidentity.com/)**  

  Enterprise identity platform offering MFA, passwordless, risk-based authentication, and identity verification capabilities.



- **[Yubico](https://www.yubico.com/)**  

  Hardware security keys (YubiKey) and supporting software for strong phishing-resistant MFA and passkeys.



- **[Authy (Twilio)](https://authy.com/)**  

  Popular multi-device authenticator app and Twilio’s broader 2FA/OTP APIs for developers and consumers.



- **[Trulioo](https://www.trulioo.com/)**  

  Global identity verification platform focused on KYC, AML, and document/biometric identity proofing.



- **[Persona](https://withpersona.com/)**  

  Modern identity verification platform offering document checks, biometrics, and orchestration for onboarding and compliance.



- **[Onfido (Entrust)](https://onfido.com/)**  

  AI-powered identity verification with document and biometric checks widely used for KYC and fraud prevention.



## Open-Source GitHub Projects

- **[privacyIDEA](https://github.com/privacyidea/privacyidea)**  

  Open-source multi-factor authentication system supporting OTP, hardware tokens, WebAuthn, and flexible policies for enterprises.



- **[Keycloak](https://github.com/keycloak/keycloak)**  

  Leading open-source identity and access management solution with built-in OTP, WebAuthn, and strong MFA support.



- **[Authentik](https://github.com/goauthentik/authentik)**  

  Modern open-source Identity Provider with MFA, WebAuthn/passkeys, flows, and flexible authentication policies.



- **[Authelia](https://github.com/authelia/authelia)**  

  Open-source authentication and authorization server providing 2FA and single sign-on for self-hosted applications.



- **[FreeOTP / FreeOTP+](https://github.com/freeotp)**  

  Open-source TOTP/HOTP authenticator apps (Android/iOS lineage) for generating one-time passwords without proprietary lock-in.



- **[Aegis Authenticator](https://github.com/beemdevelopment/Aegis)**  

  Secure, open-source Android authenticator focused on offline TOTP/HOTP with strong encryption and backup options.



- **[andOTP](https://github.com/andOTP/andOTP)**  

  Open-source Android OTP authenticator with encrypted backups and a privacy-oriented design.



- **[Ory Kratos](https://github.com/ory/kratos)**  

  Open-source identity management system supporting MFA, passwordless flows, and modern authentication patterns.



- **[Zitadel](https://github.com/zitadel/zitadel)**  

  Open-source identity infrastructure with built-in MFA, passkeys, and multi-tenancy for B2B/B2C use cases.



- **[Kanidm](https://github.com/kanidm/kanidm)**  

  Modern open-source identity management platform emphasizing security, simplicity, and strong authentication.



- **[SimpleWebAuthn](https://github.com/MasterKale/SimpleWebAuthn)**  

  Popular open-source WebAuthn/passkey libraries for implementing phishing-resistant authentication in applications.



- **[Yubico open-source projects](https://github.com/Yubico)**  

  Official open-source libraries, tools, and documentation around YubiKey, WebAuthn, and OTP from Yubico.



- **[LinOTP](https://github.com/LinOTP/LinOTP)**  

  Open-source OTP platform supporting a wide range of token types and enterprise authentication scenarios.



- **[Gluu / Janssen Project](https://github.com/JanssenProject)**  

  Open-source identity and access management components including strong authentication capabilities.



- **[WebAuthn / FIDO related libraries](https://github.com/search?q=webauthn)**  

  Community libraries and reference implementations for passkeys and FIDO2 across languages and frameworks.



### Additional Strong Open-Source Options

- Self-hosted MFA with **privacyIDEA**, **Keycloak**, **Authentik**, or **Authelia**.

- Mobile authenticators: **Aegis**, **FreeOTP**, **andOTP**, and similar open TOTP apps.

- Passkeys/WebAuthn via **SimpleWebAuthn** and language-specific FIDO2 libraries.

- Identity platforms: **Ory**, **Zitadel**, **Kanidm**, and **Janssen**.

- Hardware-backed security combined with open software (YubiKey + open WebAuthn stacks).

- Note: Full-featured commercial IDV/KYC (document + liveness + global data sources) still has limited complete open-source equivalents; most open work focuses on authentication rather than regulated identity proofing.



**Frameworks for building custom systems**: Combine **Keycloak** or **Authentik** (IdP + MFA) with **privacyIDEA** or WebAuthn libraries, plus open authenticator apps. For identity verification, open components can handle authentication while regulated IDV often still relies on commercial providers (Trulioo, Persona, Onfido, etc.). Suitable for teams prioritizing control over MFA and access while meeting compliance needs.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Identity verification and authentication systems handle sensitive personal data and access control. Ensure compliance with applicable regulations (KYC/AML, GDPR, etc.) and follow security best practices. This list is not security, legal, or compliance advice.



---

**Made for security teams, identity architects, developers, and open-source advocates.**

Let's keep identity verification and authentication strong, private, and as open as practical.
