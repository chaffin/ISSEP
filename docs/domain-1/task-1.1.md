[Domains](../index.md) | [Tasks](index.md)
---

### 1.1 General Security Principles

### 1.1.1 Identify organizational security authority

### 1.1.2 Identify elements of a system security policy

### 1.1.3 Understand trust concepts and hierarchies

### 1.1.4 Determine boundaries governed by security policies

### 1.1.5 Specify complete mediation

### 1.1.6 Determine least common mechanism

Least common mechanism  is to minimize the amount of mechanism common to more than one user and depended on by all users.[^1] Every shared mechanism (especially one involving shared variables) represents a potential information path between users and must be designed with great care to be sure it does not unintentionally compromise security.[^2]

According to Wallach, the principle of *least common mechanism* concerns the dangers of **sharing state** among different programs, suggesting that if one program can corrupt a shared state, it can then corrupt other programs which depend on it.[^3]
 
### 1.1.7 Understand open design concepts

### 1.1.8 Analyze psychological acceptability/usability

In thier manauscript "*The Protection of Information in Computer Systems*" Saltzer and Schroder cite psychological acceptability as one of eight examples of design principles that apply particularly to protection mechanisms, and maintain that "[i]t is essential that the human interface be designed for ease of use, so that users routinely and automatically apply the protection mechanisms correctly."[^4]

According to Gegick and Barnum, psychological acceptability means resources should not be inhibited by security mechanisms because users may turn off security mechanisms if they hinder usability or accessibility or resources. They suggest that where possible, security mechanisms should be transparent to the users of the system or at most be user friendly, introducing minimal obstruction to facilitate their use and understanding in a software application.[^5]

### 1.1.9 Understand the importance of consistent measurement

---
[^1]: Saltzer. "*Basic Principles Of Information Protection,*" May 10, 2013; web.mit.edu: October 17, 1997, http://web.mit.edu/Saltzer/www/publications/protection/Basic.html  

[^2]: Michael Gegick and Sean Barnum. "*Least Common Mechanism*", May 10, 2013; www.us-cert.gov: January 27, 2019; https://www.us-cert.gov/bsi/articles/knowledge/principles/least-common-mechanism  

[^3]: Wallach, Dan; Least Common Mechanism, 7/26/1997; sip.cs.princeton.edu: December 4, 1997; http://sip.cs.princeton.edu/pub/sosp97/node15.html

[^4]: Saltzer and Schroeder. "*The Protection of Information in Computer Systems*", April 17. 1975; www.cs.virginia.edu, January 27, 2019, https://www.cs.virginia.edu/~evans/cs551/saltzer/

[^5]: Michael Gegick and Sean Barnum. "*Psychological Acceptability*", May 10, 2013; www.us-cert.gov, January 27, 2019, https://www.us-cert.gov/bsi/articles/knowledge/principles/psychological-acceptability
