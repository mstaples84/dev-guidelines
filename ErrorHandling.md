# Handling Bugs and Errors
This document describes how to handle Bugs and Errors.

## Table of Contents
1. [Difference Bug / Error](#bugs-vs-errors-the-difference)
2. [Errors](#errors)
3. [Bugs](#bugs)
4. [Read more](#read-more)

## Bugs vs Errors, the difference
A Bug is an identified, technical issue that breaks functionality.
A Error may be caused by a bug or by false user input, false use or any other human 
or infrastructure issue, such as corrupted network connectivity or a hardware fault.

## Errors
When encountering an error, the first level support is the first contact. Errors are not 
submitted as a Bug Ticket in any case. Only the first level support may input Bug Tickets 
after running Tests by the protocol. The protocol document will be provided to all first level 
support members.

## Bugs
Bugs are technical issues within the system in use. Most likely, bugs require a developer to 
investigate further cause. The Bug Ticket doesn't follow the Feature Request Workflow. It will 
be prioritized depending on the effect on the system and stakeholders. 

The bugfix is released depending in a hotfix. The hotfix is sub versioned. Read more about 
Versioning [here](README.md#versioning).

Developers select bugs to fix by this criteria:

1. The module or feature effected: The developer possibly most familiar with the feature will be assigned.
2. Criticality: Critical bug tickets first, then medium, and finally low.

# Read more
[Home](README.md)