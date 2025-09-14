---
layout: post
title: How a 10-Minute Phone Call Brought Down MGM (And How to Protect Yourself at Work)
cover-img: 
thumbnail-img:
share-img:
tags: [certification, CompTIA network+]
author: Maxime Siffert
---
*The $100 million lesson in workplace security that every employee needs to understand*

On September 11, 2023, a company valued at $33.9 billion was defeated by a 10-minute conversation.

MGM Resorts—one of the world's largest casino and entertainment companies—was brought to its knees not by sophisticated hacking tools or years of planning, but by a simple phone call to their help desk.

The attackers, a group called Scattered Spider, used LinkedIn to identify a current MGM employee, then called MGM's help desk posing as that employee asking for help logging into their account. The person on the phone said they had forgotten their password and gave personal information that "all checked out."

Within minutes, the help desk had reset passwords and multi-factor authentication codes for high-value MGM employees, giving the attackers access to MGM's entire network.

The result? Ten days of casino shutdowns, guests locked out of rooms, slot machines down, and losses reaching eight figures.

This wasn't a failure of technology. This was a failure of workplace security awareness that could happen at any company, including yours.

## The Anatomy of the MGM Attack: What Actually Happened

Let me break down exactly how this attack worked, because understanding the method is crucial to protecting yourself.

### Step 1: LinkedIn Research (5 minutes)
The attackers used LinkedIn to find MGM employees and gather information about them. LinkedIn profiles often contain:
- Full names and job titles
- Department information
- Work history and start dates
- Professional connections and relationships
- Sometimes personal interests and background details

### Step 2: The Social Engineering Call (10 minutes)
The attackers called MGM's help desk and said they were an employee who had forgotten their password. They used the LinkedIn research to provide convincing personal details when asked to verify their identity.

Here's the critical failure: The help desk agent was able to be convinced without being forced to authenticate through another factor.

### Step 3: System Access and Escalation
Once they convinced the help desk to provide login credentials, the attackers infiltrated MGM's network systems. They gained access to reset passwords and MFA codes of high-value employees, giving them administrative control over MGM's systems.

### Step 4: Ransomware Deployment
Interestingly, the hackers claim this was not initially planned as a ransomware attack but evolved into one. The attack led to critical operational disruptions as the attackers deployed ransomware across MGM's network.

## Why This Attack Worked: The Human Firewall Failure

The MGM attack succeeded because it exploited the gap between technical security systems and human behavior. MGM likely had:
- Strong passwords requirements
- Multi-factor authentication systems  
- Network security tools
- Expensive cybersecurity software

But none of that mattered because the attackers exploited human vulnerabilities to extract critical credentials.

This is exactly what I mean by the "Human Firewall" concept: **your technical security is only as strong as the humans operating it.**

## The Five Critical Vulnerabilities the MGM Attack Exposed

### Vulnerability 1: Public Professional Information
**The Problem:** Everything attackers needed to begin their social engineering was publicly available on LinkedIn.

**Your Protection Strategy:**
- **Audit your LinkedIn profile:** Remove or limit personal details like exact start dates, specific departments, or personal background information
- **Review other professional profiles:** Check company websites, conference speaker bios, and professional directories for information that could be used against you
- **Educate your team:** If you're in a leadership position, help colleagues understand how their public information can be weaponised

### Vulnerability 2: Help Desk Social Engineering
**The Problem:** MGM's help desk accepted personal information as sufficient verification for password resets.

**Your Protection Strategy:**
- **Know your company's verification procedures:** Understand exactly how IT verifies identity before helping with account issues
- **Suggest improvements:** If your company's procedures seem weak, suggest additional verification steps through proper channels
- **Be suspicious of unusual IT contact:** If someone claiming to be from IT contacts you unexpectedly, verify their identity through a separate channel

**If you work in IT or support:**
- **Never rely solely on personal information** for verification (this information can be researched)
- **Implement multi-factor verification** for sensitive requests (callback to registered number, in-person verification, supervisor approval)
- **Be extra cautious of urgent requests** that pressure you to bypass normal procedures

### Vulnerability 3: Excessive Trust in Internal Systems
**The Problem:** Once attackers gained initial access, they could escalate privileges because systems trusted "authenticated" users.

**Your Protection Strategy:**
- **Question unusual access requests** even from apparent colleagues or IT staff
- **Verify sensitive requests through separate channels:** If someone asks for passwords, system access, or financial information, confirm through a different communication method
- **Report suspicious activity immediately:** Don't worry about being wrong; security teams prefer false alarms to missed real threats

### Vulnerability 4: Information Concentration Risk
**The Problem:** The attackers gained access to "high-value MGM employees" whose credentials provided extensive system access.

**Your Protection Strategy:**
- **Understand your access level:** Know what systems and information your credentials can access
- **Use principle of least privilege:** Only request access to systems you actually need for your job
- **Secure high-privilege accounts extra carefully:** If you have administrative or sensitive access, use additional security measures like dedicated devices or enhanced authentication

### Vulnerability 5: Inadequate Incident Response
**The Problem:** The attack resulted in 10 days of operational disruption, suggesting detection and response systems weren't adequate.

**Your Protection Strategy:**
- **Know how to report security incidents** in your organisation
- **Understand warning signs** of compromise (unusual system behavior, unexpected access requests, strange network activity)
- **Document suspicious activities:** Keep records of unusual requests or incidents that might be part of a larger attack

## Practical Workplace Security Lessons from MGM

### Lesson 1: Your Public Information is Attack Intelligence

**What to do immediately:**
- **Review all your professional online profiles** (LinkedIn, company website, conference bios, social media)
- **Remove or limit personal details** that could be used for verification questions (birth dates, hometown, education details, family information)
- **Use privacy settings** to limit who can see detailed professional information
- **Be cautious about what you share** in professional forums, comments, or public posts

### Lesson 2: Verification Systems Can Be Defeated

**What to do immediately:**
- **Learn your company's IT verification procedures** and suggest improvements if they seem weak
- **Establish verification codes or questions** with your immediate team for sensitive requests
- **Create separate communication channels** for verifying unusual requests (if someone emails you urgently, call them back using a known number)
- **Never provide credentials** to anyone who contacts you, regardless of how official they sound

### Lesson 3: Social Engineering Exploits Professional Courtesy

**What to do immediately:**
- **Practice saying no** to requests that feel unusual or urgent
- **Implement waiting periods** for sensitive requests (24-hour rule for financial or access changes)
- **Question authority appropriately:** It's better to verify a legitimate request than to enable a security breach
- **Train yourself to recognise pressure tactics:** Urgency, authority, and helpfulness are commonly exploited emotions

### Lesson 4: Individual Actions Affect organisational Security

**What to do immediately:**
- **Understand your role** in your organisation's security posture
- **Report security training needs** if you identify gaps in your knowledge or your colleagues'
- **Participate actively** in security awareness programs
- **Share security knowledge** appropriately with colleagues (without violating policies)

## What Your Company Should Learn from MGM

If you're in a position to influence security policies at your organisation, the MGM attack highlights several critical areas for improvement:

### Stronger Identity Verification
- **Multi-factor verification** for all sensitive help desk requests
- **Callback procedures** using independently verified contact information
- **Supervisor approval** for high-risk account changes
- **Documentation requirements** for all identity verification attempts

### Enhanced Social Engineering Awareness
- **Regular training** that includes current attack methods like the MGM scenario
- **Simulated attacks** to test employee and help desk response
- **Clear reporting procedures** for suspicious contact attempts
- **Incident response plans** that include social engineering scenarios

### Professional Information Security
- **Guidelines for employee online presence** and professional information sharing
- **Regular assessment** of publicly available information about employees and systems
- **Coordination between HR, IT, and Security** on information exposure risks
- **Executive protection programs** for high-value targets within the organisation

## The Broader Implications: Why This Matters Beyond MGM

The MGM attack isn't an isolated incident. Scattered Spider is a cybercriminal group that targets large companies and their IT help desks as a standard method. Similar attacks have targeted:

- Healthcare organisations with access to patient data
- Financial services with access to customer accounts
- Technology companies with valuable intellectual property
- Government agencies with sensitive information
- Educational institutions with research and student data

**The method works because it exploits fundamental human psychology:**
- **Authority**: People tend to comply with requests from apparent authority figures
- **Helpfulness**: Employees are trained to be helpful and accommodate requests
- **Trust**: Professional environments encourage trust and collaboration
- **Urgency**: Time pressure reduces critical thinking and verification behaviors

## Protecting Yourself in the Post-MGM World

### Personal Security Mindset Changes

**Adopt "Trust but Verify" Thinking:**
- **Assume good intentions** while implementing verification procedures
- **Separate emotion from process:** Urgency and authority should trigger verification, not immediate compliance
- **Make verification automatic:** Develop habits that don't depend on remembering to be suspicious

**Professional Boundary Setting:**
- **Understand what information you can safely share** and what requires verification
- **Establish clear procedures** for handling unusual requests
- **Communicate your security practices** to colleagues so they understand your verification steps

### Technical and Procedural Protections

**Enhanced Authentication Awareness:**
- **Understand what good verification looks like** in your organisation
- **Know the difference** between authentication (proving who you are) and authorisation (proving what you can access)
- **Recognise when verification procedures are insufficient** and advocate for improvements

**Information Compartmentalisation:**
- **Limit public professional information** to what's necessary for legitimate business purposes
- **Use privacy settings** consistently across all professional platforms
- **Regularly review and clean up** information about yourself that could be used maliciously

## The Human Firewall in Action

The MGM attack perfectly illustrates why I focus on the "Human Firewall" concept in cybersecurity. The attackers exploited human vulnerabilities to extract critical credentials, bypassing all of MGM's technical security measures.

But here's the crucial insight: **humans can also be the strongest part of security systems.**

If MGM's help desk agent had:
- **Required additional verification** beyond personal information
- **Implemented a callback procedure** to a verified number
- **Applied a waiting period** for sensitive account changes
- **Consulted a supervisor** for unusual requests

The entire attack would have failed at the first step.

## Your Role in organisational Security

Whether you're an entry-level employee or a senior executive, you have a role in preventing MGM-style attacks at your organisation:

**As an Individual Employee:**
- **Practice good security hygiene** in your own work
- **Question suspicious requests** appropriately
- **Report potential security incidents** promptly
- **Participate actively** in security training and awareness programs

## The Bottom Line: Every Phone Call is a Security Decision

The MGM attack shows how a single 10-minute conversation can bring down a $33.9 billion company. But it also shows how individual security awareness can prevent catastrophic organisational failures.

Every time you:
- **Answer a call** from someone claiming to be from IT
- **Respond to an email** requesting personal or account information  
- **Provide verification information** to authenticate yourself
- **Share professional information** online or in conversations

You're making a security decision that could affect not just you, but your entire organisation.

## What's Your MGM Moment?

Think about your own workplace for a moment:
- **How would your IT help desk verify your identity** if you called asking for a password reset?
- **What personal information** could someone find about you on LinkedIn or other professional sites?
- **How would you respond** if someone claiming to be from IT called you asking for verification information?
- **What would happen** if your credentials were compromised like MGM's employees?

These aren't hypothetical questions. The MGM attack shows how social engineering can snowball into weeks of downtime and eight-figure losses for any organisation.

But they're also not unsolvable problems. Good workplace security awareness, combined with practical verification procedures, can stop these attacks at the first step.

---

*I am building expertise in human-centered cybersecurity by analysing real-world attacks and developing practical protection strategies. Currently working through CompTIA Network+ after completing A+ Core 1 and Core 2. What workplace security challenges have you encountered, and how has your organisation addressed social engineering threats?*
