---
###
# Internet-Draft Markdown Template
#
# Rename this file from draft-todo-yourname-protocol.md to get started.
# Draft name format is "draft-<yourname>-<workgroup>-<name>.md".
#
# For initial setup, you only need to edit the first block of fields.
# Only "title" needs to be changed; delete "abbrev" if your title is short.
# Any other content can be edited, but be careful not to introduce errors.
# Some fields will be set automatically during setup if they are unchanged.
#
# Don't include "-00" or "-latest" in the filename.
# Labels in the form draft-<yourname>-<workgroup>-<name>-latest are used by
# the tools to refer to the current version; see "docname" for example.
#
# This template uses kramdown-rfc: https://github.com/cabo/kramdown-rfc
# You can replace the entire file if you prefer a different format.
# Change the file extension to match the format (.xml for XML, etc...)
#
###
title: "Derivative Works"
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

This document clarifies that IETF correspondence must not contain legal limitations on derivative works.

--- middle

# Introduction

This document updates Rights Contributors Provide to the IETF Trust {{RFC5378}}
in order to clarify and limit which contributions may include a restriction on derivative rights.

# Conventions and Definitions

{::boilerplate bcp14-tagged}

# Derivative Works

There is an expansive definition of "Contribution" in {{RFC5378}}. There is also a mechanism formally defined in Section 5.3 of that RFC that allows a Contributor to limit the right to produce derivative works. As written, this optional mechanism applies to all Contributions. Using this mechanism outside of specifications, for example, in electronic mail, makes it difficult for people to respond and inhibits collaboration. This behavior impedes the very idea of collaborating about the Internet over the Internet. The IESG has stated {{IESG-DERIV}} that derivative works limitations should only be applied to technical specifications.

This document narrows the use of this mechanism to technical specifications, such as Internet-Drafts or other complete specifications. It no longer applies to correspondence, such as public online IETF fora as defined in {{RFC9945}}, appeals, minutes, or audio or video recordings of IETF meetings.

Such IETF correspondence MUST NOT include restrictions on derivative works. This restriction covers text that is intentionally inserted and also includes automatically inserted terms inserted by corporate email software. Both variations are disruptive.

It is always possible to publish an Internet-Draft with a restrictive derivative works clause.

When introducing a document with such a clause, care must be taken to note the restriction. This consideration applies to email and IETF meeting presentations.

All other rights Contributors provide to the IETF Trust {{RFC5378}} remain in place.

# Security Considerations

This document has no direct impact on Internet security.

# IANA Considerations

This document has no IANA actions.


--- back
