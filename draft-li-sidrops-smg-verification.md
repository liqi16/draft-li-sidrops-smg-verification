---
title: "Signed MOAS Group (SMG) Based Route Origin Verification and Operational Considerations"
abbrev: "smg-verification"
category: info

docname: draft-li-sidrops-smg-verification-latest
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: "Operations and Management"
workgroup: "SIDR Operations"
keyword:
 - next generation
 - unicorn
 - sparkling distributed ledger
venue:
  group: "SIDR Operations"
  type: "Working Group"
  mail: "sidrops@ietf.org"
  arch: "https://mailarchive.ietf.org/arch/browse/sidrops/"
  github: "liqi16/draft-li-sidrops-smg-verification"
  latest: "https://liqi16.github.io/draft-li-sidrops-smg-verification/draft-li-sidrops-smg-verification.html"

author:
 -
    fullname: "LIQI"
    organization: Your Organization Here
    email: "59596741+liqi16@users.noreply.github.com"

normative:

informative:


--- abstract

The Signed MOAS Group (SMG) is a Cryptographic Message Syntax (CMS) protected content type that allows multiple Autonomous Systems (ASes) to collaboratively and securely announce an IP prefix in the Border Gateway Protocol (BGP). This document specifies the SMG-based Route Origin Verification (SMG-ROV) methodology, designed to enhance the security of multi-origin AS (MOAS) scenarios in the BGP. By combining SMG-ROV with ROA-based ROV (ROA-ROV), the document provides a mechanism to distinguish between legitimate MOAS and malicious prefix hijacks, thereby mitigating prefix hijacks and AS forgery.  The document also explains the various BGP security threats that SMG can help address and provides operational considerations associated with SMG-ROV deployment.


--- middle

# Introduction

TODO Introduction


# Conventions and Definitions

{::boilerplate bcp14-tagged}


# Terminology and List of Acronyms

The following list includes the terms used with special meanings and acronyms.

# Signed MOAS Group (SMG) and Validated SMG Payload (VMP)

# Route Origin Verification Algorithms Using ROA and SMG

# Mitigation Policy

# BGP Security Threats Addressed by SMG-ROV

# Operational Considerations

# Security Considerations

TODO Security

# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
