---
title: "Clarification of Derivative Works Restrictions"
category: bcp

updates: 5378
docname: draft-sayre-gendispatch-derivative-latest
submissiontype: IETF
number:
date:
consensus: true
v: 3
area: GEN
workgroup: General Area Dispatch
keyword:
 - derivative
venue:
  group: WG
  type: General Area Dispatch
  mail: gendispatch@ietf.org
  arch: https://datatracker.ietf.org/group/gendispatch/documents/

author:
 -
    fullname: Robert Sayre
    city: San Francisco
    region: CA
    country: United States of America
    email: sayrer@gmail.com

 -
    ins: B. E. Carpenter
    name: Brian E. Carpenter
    org: The University of Auckland
    abbrev: Univ. of Auckland
    postal:
    - School of Computer Science
    - The University of Auckland
    - PB 92019
    - Auckland 1142
    country: New Zealand
    email: brian.e.carpenter@gmail.com

normative:
  RFC5378:
  RFC9945:

informative:
  IESG-DERIV:
    target: https://datatracker.ietf.org/doc/statement-iesg-statement-on-clarifying-derivative-works-rights/
    title: IESG Statement on Clarifying Derivative Works Rights
    author:
      - org: IESG
    date: 2025-10

...

--- abstract

This document clarifies that only IETF Documents may contain legal limitations on derivative works.

--- middle

# Introduction

This document updates Rights Contributors Provide to the IETF Trust {{RFC5378}}
in order to clarify and limit which contributions may include a restriction on derivative rights.

# Conventions and Definitions

<!-- {::boilerplate bcp14-tagged} -->

This document uses the terminology defined in {{RFC5378}}.

# Derivative Works

There is an expansive definition of "Contribution" in {{RFC5378}}. There is also a mechanism formally defined in Section 5.3 of that RFC that allows a Contributor to limit the right to produce derivative works. As written, this optional mechanism could be misconstrued as applying to all Contributions. Using this mechanism outside of specifications, for example, in electronic mail, makes it difficult for people to respond and inhibits collaboration.  This behavior impedes the very idea of collaborating about the Internet over the Internet. The IESG has stated {{IESG-DERIV}} that derivative works limitations should only be applied to IETF Documents as defined in {{RFC5378}}.

This document clarifies that Section 3.3 of RFC 5378 permits the use of this mechanism only for the text of IETF Documents, i.e., RFCs or Internet-Drafts that are used in the IETF Standards Process. Derivative works restrictions may not be applied to other Contributions, such as public online IETF fora as defined in {{RFC9945}}, appeals, minutes, or audio or video recordings of IETF meetings.

All other rights Contributors provide to the IETF Trust/ICMP {{RFC5378}} remain in place.

# Security Considerations

This document has no direct impact on Internet security.

# IANA Considerations

This document has no IANA actions.


--- back

# Change Log [RFC Editor, please remove]

## Draft-00

- Original version

## Draft-01

- Added author, expanded argument

## Draft-02

- Removed pointless sentence

## Draft-03

- Significant rewording

## Draft-04

- Update after IETF 126 discussion

# Acknowledgements
{:numbered="false"}

Helpful comments were made by
Roman Danyliw,
Paul Wouters,
...
