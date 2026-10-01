# 🔐 My TryHackMe Cybersecurity Journey

This repository is where I document some of the cybersecurity labs and practical things I learn while using TryHackMe.

I am currently learning cybersecurity alongside my BSc in Information Technology and the Google Cybersecurity Certificate. I want to use these labs to gain practical experience, not just learn the theory.

## 🧪 Completed Rooms

### 1. Offensive Security Intro

**Status:** ✅ Completed

This was one of my first introductions to offensive security. I learned how attackers can look for weaknesses in a system and how security testing can be used to find those weaknesses.

One of the things I practiced was using **DIRB** with a website URL to enumerate directories and discover pages that were not linked from the main website.

During the lab, I found an unlinked admin page. I noticed that there was no proper login or authentication before accessing information and functionality in the application.

I was able to access the admin area and modify a test account balance. This made me understand that simply hiding an admin page is not enough. Sensitive information and administrative functions should be protected by proper authentication and authorization.

The entire exercise was done inside the authorized TryHackMe lab environment.

### 2. Defensive Security Intro

**Status:** ✅ Completed

This room gave me an introduction to the defensive side of cybersecurity and how security incidents can be investigated.

During the lab, I came across suspicious activity involving multiple logins to a user's bank account.

I first copied the affected account information and closed the account in the lab to help contain the situation before continuing with the investigation.

After investigating the activity, I found information about the attacker and also discovered that this was not the attacker's first attempt.

The investigation showed that the attacker was using an automated script to try thousands of accounts within a few minutes.

This was interesting to me because it showed me how important it is to look at patterns in login activity rather than treating every suspicious login as an isolated event.

## 🧰 Things I Practiced

- DIRB
- Directory enumeration
- Finding unlinked pages
- Web security
- Authentication and authorization
- Access control
- Investigating suspicious login activity
- Account compromise investigation
- Incident containment
- Evidence preservation
- Identifying automated attacks

## 🎯 What I Am Learning

Through these labs, I am getting more comfortable with both offensive and defensive security.

I am currently continuing to learn about:

- Cybersecurity fundamentals
- Networking
- Linux
- Web security
- Incident response
- Threat detection
- Security investigations

## 📚 Learning Platforms

- TryHackMe
- Google Cybersecurity Certificate
- GitHub

> All practical activities documented here were performed in authorized cybersecurity training environments.
