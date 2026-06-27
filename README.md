# Okta IAM Implementation

Identity and Access Management implementation using Okta, built during an internship at Razz Security (March–April 2026). Configured and tested on Razzify, an internal web application used as the integration environment.

## What Was Implemented

- *SSO* — configured OIDC-based authentication flow between Razzify and Okta as the Identity Provider
- *MFA Policies* — enforced multi-factor authentication at the application and group level
- *RBAC* — created user groups with role-based access, assigned applications per role
- *User Lifecycle Management* — user provisioning, deprovisioning, and group assignment workflows
- *JWT Token Analysis* — inspected ID tokens and access tokens to verify claims and scopes

## Authentication Flow

User → Razzify → Redirect to Okta → Credentials + MFA → ID Token + Access Token → Access Granted

## Tools & Protocols

- Okta (Identity Provider)
- OpenID Connect (OIDC) / OAuth 2.0
- Secure Web Authentication (SWA)
- JWT (JSON Web Tokens)

## Key Takeaways

- SSO centralises authentication and reduces per-app credential sprawl
- RBAC misconfiguration leads to privilege creep — users retaining access they no longer need
- JWT claims can expose sensitive group membership if not scoped correctly

  


## Documentation
📄 [Download Report] https://github.com/vaibhavkrishna12004/okta-demo-app/blob/be12308ef44901f13da9e1bab4bf7211efb87134/OKTA%20.pdf




 
