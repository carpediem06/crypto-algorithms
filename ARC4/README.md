Arcfour
=================


About
---
In cryptography, RC4 (Rivest Cipher 4 also known as ARC4 or ARCFOUR meaning Alleged RC4, see below) is a stream cipher. While it is remarkable for its simplicity and speed in software, multiple vulnerabilities have been discovered in RC4, rendering it insecure.[3][4] It is especially vulnerable when the beginning of the output keystream is not discarded, or when nonrandom or related keys are used. Particularly problematic uses of RC4 have led to very insecure protocols such as WEP.[5]

As of 2015, there is speculation that some state cryptologic agencies may possess the capability to break RC4 when used in the TLS protocol.[6] IETF has published RFC 7465 to prohibit the use of RC4 in TLS;[3] Mozilla and Microsoft have issued similar recommendations.[7][8]

A number of attempts have been made to strengthen RC4, notably Spritz, RC4A, VMPC, and RC4+.

Demo
---

```gcc arcfour -o arcfour_test.c arcfour.c
```
