# [Software Engineering Markdown Templates](../readme.md)

## Secure Coding Standards

This document contains the Secure Coding Standards Documentation for Project ABC.

### Known Attack Vectors

Software in this category is known to be vulnerable to XYZ attacks. No attacks have been found at this time.

### Coding Standards

#### Array Bounds Checking

Array bounds checking is to be performed on all data that is not known to be a C-style string at compile time. All functions requiring bounds checking shall pass in the base address of the Socket and the last address of of the Socket. Each function shall also contain an additional function that takes the size of the buffer as a word-sized signed integer to use with implied up-casting.

#### Input Sanitation

All data from the outside world shall be sanitized by ABC Sanitation Method. ABC Sanitation Method shall be performed XYZ to protect from Attack Vectors 1, 2, and 3.

#### Interprocess Memory

Unused interprocess memory sockets shall be set to all zeros upon completion of the construction and initial population of the object before the Socket becomes visible to the outside world in order to not expose arbitrary stack data.
