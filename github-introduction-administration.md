# Title

Introduction to GitHub Administration

## Role(s)

- administrator
- devops-engineer
- technology-manager

## Level

- intermediate

## Product(s)

- github

## Prerequisites

- Familiarity with GitHub, repositories, and the basics of managing individual accounts is required.
- Familiarity with personal and organizational authentication technologies and processes would be very helpful.

## Summary

  TBD

## Learning objectives

[See note #1 at bottom]

1. Describe how GitHub administrators can utilize various technologies to enable a secure authentication strategy allowing them to centrally manage repository access.
2. Describe how GitHub administrators can organizes members into organizations and teams to control access and privacy.
3. Describe how GitHub administrators can centrally manage teams and members using existing directory information services.
4. Describe how GitHub can itself be used as an identity provider for authentication and authorization.


## Outline the units

1. **Introduction**

    TBD

1. **What is GitHub Administration?**

    - Overview of typical GitHub administration tasks
    - Overview of GitHub team structures, membership, and privacy
    
1. **How does GitHub Authentication work?**

    - Describe how users can be authenticated:
        - Define how GitHub administrators can use MFA and SSO as means of authenticating users.
        - Describe how SSH keys are used for accessing GitHub repositories.
        - Explain how personal access tokens can be used for authentication to GitHub when using the GitHub API or command line.        
    - Describe how administrators can control membership and authentication:
        - Summarize how you can use LDAP to access GitHub Enterprise Server using existing accounts and centrally manage repository access.
        - Describe how GitHub Enterprise Server can act as a service provider with your internal SAML identity provider.

1. **How does GitHub organization and permissions work?**

    - Describe the different groupings and purpose of users and resources:
        - Repository
        - Team
        - Organization
    - Describe the different levels of permissions for a given repository:
        - Administrator
        - Owner
        - Member

1. **Knowledge check**

    - TBD
    - TBD
    - TBD

1. **Summary**

    How did you solve the problem in the initial scenario with the knowledge learned in the module? 
    
    *Add your summary [(Summary guidance)](https://review.docs.microsoft.com/en-us/learn-docs/docs/id-guidance-module-summary-unit)*

## Notes

Note 1: In the section Learning Objectives, I summarized the bullets Aaron created into two simplified high-level topics.  This makes a huge assumption that I still need to learn more about, namely, that SSO via SAML or LDAP are two options for organizational use, but administration of individual users via SSH and PAT could also be used.  (MFA will be presented as a technique organizations can use to implement SSO).  Admittedly, I've got a lot of learning to do here, and I may need to revise these LO's as I get clearer on the relationship that each of these have to one another.