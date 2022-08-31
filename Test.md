# Azure B2C Design
- [Background](#Background)
- [Scope of Document](#Scope-of-Document)
- [Definitions and Abbreviations](#Definitions-and-Abbreviations)
- [Assumptions](#Assumptions)
- [Design Decisions](#Design-Decisions)
- [Design](#Design)


# Background
- Brands is a ‘livestock’ registration project, with currently approximately 18,000 livestock owners.  The Brands project is leveraging a cloud-based registration service provided by Objective Regtech.Brands is a driver behind the Azure AD B2C (B2C) project. B2C is required to support authentication for this project, along with providing a ‘validated digital identity’ via DGov/MyGovID to replace current Brands paper forms and paper signatures. This wiki details the design and configuration details required to implement Azure B2C

# Scope of Document
- WA IDX Onboarding
- Create B2C Tenant
- Configure Custom policies
# Definitions and Abbreviations

|   Item   | Value  | 
|--------|---------|
| B2C | Businees to Consumer  |

# Assumptions

# Design Decisions

|   Item   | Value  | 
|--------|---------|
| DD1 | B2C tenant name is wagov01auth  | 
| DD2 | B2C solution need not cater for DPIRD users . External users(Customers) are the only target users. DPIRD Admin users will use backend system to login Brands application  | 
| DD3 | Administrators in B2C tenant should be configured for MFA  | 
| DD4 | Users need to authenticate only by MyGovID.Social Account login isn't required | 
| DD5 | Assurance level is IP2 CL2  |
| DD5 | B2C defalut URLs shouldn't be exposed .Custom URLs need to be published  |

# Design

![Alt](download.png)






