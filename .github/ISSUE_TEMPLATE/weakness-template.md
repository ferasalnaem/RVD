---
name: Weakness report template
about: Template to report a weakness in RVD. See https://bit.ly/2JnamaD if in doubt
title: ''
labels: weakness
assignees: ''

---

# Weakness report

| Input      | Value  |
|---------|--------|
| Robot (or robot component) name | <ins>`required`</ins> |
| Vendor  | `optional`  |
| CVE ID  | `optional`, if exists  |
| CWE ID  | <ins>`required`</ins>, refer to https://cwe.mitre.org/data/pdf/1000_abstraction_colors.pdf for help  |
| Module URL | 	`optional`, *link to docker image to reproduce flaw* |
| Attack vector | <ins>`required`</ins> e.g.: Local network or Physical access |

### Description:

*Please provide a brief description of the vulnerability and how to reproduce it*