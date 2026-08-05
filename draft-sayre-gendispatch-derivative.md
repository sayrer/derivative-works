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

This document clarifies that only IETF Documents may contain legal limitations on derivative works.

--- middle

# Introduction

This document updates Rights Contributors Provide to the IETF Trust {{RFC5378}}
in order to clarify and limit which contributions may include a restriction on derivative rights.

# Conventions and Definitions

<!-- {::boilerplate bcp14-tagged} -->

This document uses the terminology defined in {{RFC5378}}.

# Derivative Works

Section 1 of {{RFC5378}} defines "Contribution", a "Contributor" and "IETF Documents". Sections 5.3 and 6 of RFC 5378 describe an optional mechanism for a Contributor to limit derivative works rights with a notice in the Contribution.

This optional mechanism has sometimes been misconstrued as applying to all Contributions. Using this mechanism outside of specifications, for example, in electronic mail, makes it difficult for people to respond and inhibits collaboration.  This behavior impedes the very idea of collaborating about the Internet over the Internet. The IESG has previously issued a statement on this topic {{IESG-DERIV}}.

This document clarifies with normative effect that RFC 5378 permits the use of this mechanism only for the text of IETF Documents, i.e., RFCs or Internet-Drafts that are used in the IETF Standards Process.

__Question for legal review:__ Which of the following two alternative sentences would be more effective and less problematic for participants?

__Version 1:__ Derivative works restrictions may not be applied to other Contributions, such as but not limited to public online IETF fora as defined in {{RFC9945}}, appeals, minutes, or audio or video recordings of IETF meetings.

__Version 2:__ Derivative works restrictions attached to other Contributions, such as but not limited to public online IETF fora as defined in {{RFC9945}}, appeals, minutes, or audio or video recordings of IETF meetings, have no validity and should be ignored by all IETF participants.

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

## Draft-05

- Sharpened definitions taken from RFC5378
- Avoided paraphrasing IESG statement
- Added explicit  "ban vs ignore" choice
- Added explicit legal query

# Acknowledgements
{:numbered="false"}

Helpful comments were made by
Jay Daley,
Roman Danyliw,
Stephen Farrell,
Joel Halpern,
Christian Huitema,
John Klensin,
Eliot Lear,
John Levine,
Rich Salz,
Paul Wouters,
...
