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
workgroup: Network Working Group
keyword:
 - derivative
venue:
  mail: ipr-wg@ietf.org

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

This document updates RFC 5378 to clarify that only IETF Documents may contain legal limitations on derivative works.

--- middle

# Introduction

This document updates "Rights Contributors Provide to the IETF Trust" {{RFC5378}}
in order to clarify and limit which contributions may include a restriction on derivative rights.

Sections 5.3 and 6 of RFC 5378 describe an optional mechanism for a Contributor to limit derivative works rights with a notice in the Contribution.

This optional mechanism has sometimes been misconstrued as applying to all Contributions. Using this mechanism outside of specifications, for example, in electronic mail, makes it difficult for people to respond and inhibits collaboration.  This behavior impedes the very idea of collaborating about the Internet over the Internet. The IESG has previously issued a statement on this topic {{IESG-DERIV}}.

# Conventions and Definitions

<!-- {::boilerplate bcp14-tagged} -->

This document uses the terminology defined in Section 1 of {{RFC5378}}.

# Derivative Works Clarification

The No Derivative Works mechanism is limited to IETF Contributions which are Internet-Drafts and RFCs that are used in the IETF Standards Process, and is not applicable to any other IETF Contribution types as defined by RFC 5378.

All other rights Contributors grant to the IETF Trust or IETF IPMC per {{RFC5378}} remain in place.

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

## Draft-05

- Sharpened definitions taken from RFC5378
- Avoided paraphrasing IESG statement
- Added explicit  "ban vs ignore" choice
- Added explicit legal query

## Draft-06

- More succinct version
- Removed explicit legal query
- Editorial fixes

# Acknowledgements
{:numbered="false"}

Helpful comments were made by
Jay Daley,
Roman Danyliw,
Glenn Deen,
Stephen Farrell,
Joel Halpern,
Christian Huitema,
John Klensin,
Eliot Lear,
John Levine,
Rich Salz,
Paul Wouters,
and other members of the community.
