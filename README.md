# Email-Security-Checklist

The key is to asking right questions to get right answers. Here you can read my questions, concerns and problems that I faced to create Email Security Checklist.

## Identify: Enterprise Email Architecture
  - How inbound email flow works? Which path an email has to follow to reach the mailbox of an end user? 
  - Is everything as expected to be? Is there any other outbound email delivery path caused by incorrect configurations? Is there inbound e-mail traffic flow that is not   controlled by security products?
  - What if your only email security solution fails? Have you ever considered about building redundancy by working with more than one and different security vendors?
  - What is the reason of succesful cyber atack against your organization? Is there any vulnerability or misconfiguration in your defense mechanism?
  - Did you prioritized your email security policies correctly? What if your policies crushing each other and this situation cause an incident?
  - Do you collect and store your email activity logs into centralized SIEM solution? How long you should store historical email logs ?  Is there any regulation you have   to comply with?


## Protection: Inbound Email Flow
  - How you can prevent your organization from Spoofing, Domain, Impersonation, Phishing or BEC (Business Email Compromise) attacks?
  - Are you aware that benign website content can be changed with malicious one after URL attached email delivered to end users?
  - Does your email security gateway provide sandboxing capabilities to analyze attached files?
  - What about API and dynamic blacklist integration? Reputation of email senders can be automatically checked and blocked by using trusted blacklist.
  
  
  ## Protection: Outbound Email Flow
  - Does your DNS records configured correctly and includes actual information about your authorized outbound email servers?
  - Do you protect your domain from being blacklisted? Do you care about trustworthiness of your organization to business partners and customers?
  - What if a legitimate user fell for a phishing scam or had their password compromised and becomes a spammer?
  - Are you aware that your sensitive and confidential data can be exfiltrated via email channel?
  
  
  ## Detection: Alert Triggering for Malicious/Suspicious Email Activity
  - Do you get alerts if a phishing email delivered to end user for some reason?
  - Are you able to detect if a malicious URL clicked by user?
  - Can your products correlate and alert you if series of processes triggered after user open malicious email attachment?
  - Do you keep your knowledge updated identify attacker TTPs?
  
  
  ## Response/Remediation: Response and Remediation Actions for Email Related Incidents
  - Are you ready for disaster scenarios?
  - Have you every tested capabilities of your security solutions?
  - Which actions should be taken if your environment compromised by attackers?
