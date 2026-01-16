# Email Spam Filtering & Security (cPanel)

## Overview
This project documents a real-world ICT support task focused on investigating and improving email spam handling for a small business client using cPanel.

The work involved reviewing existing global email filters, analysing spam behaviour, and applying targeted improvements through blacklist rules while ensuring legitimate business emails were not disrupted. All client-specific information has been excluded to maintain privacy.

---

## Problem
The client reported ongoing spam notifications despite emails being routed to the Junk folder.  
Key concerns included:
- Repeated spam notifications on user devices
- Uncertainty around whether filtering was working correctly
- Risk of over-blocking legitimate business emails

---

## Scope of Work
- Review existing global and mailbox-level spam filters
- Analyse repeated spam sender patterns
- Apply targeted blacklist rules
- Validate filtering behaviour across email platforms
- Document findings and outcomes

---

## Tools & Environment
- cPanel (Spam Filters and Email Filters)
- Apache SpamAssassin
- Business email hosting environment
- Outlook and Roundcube (end-user behaviour review)

---

## Investigation & Actions
- Reviewed existing **global email filters** powered by Apache SpamAssassin
- Confirmed that global filtering rules were already active at the account level
- Analysed repeated spam sender domains and patterns
- Determined that broad wildcard or country-based blocking would be unsafe
- Applied **targeted spam blacklist rules** for specific repeated senders
- Avoided aggressive filtering that could impact legitimate business emails
- Explained differences in spam notification behaviour across Outlook and webmail
- Ensured changes aligned with best practices for email security and usability

---

## Configuration Screenshots

The screenshots below demonstrate the configuration approach used within cPanel.  
All images have been cropped to remove client-identifying information.

### Global Email Filtering (SpamAssassin)
![Global Email Filter](3.jpg)

### Targeted Spam Blacklist
![Spam Blacklist](4.jpeg)

---

## Validation & Outcome
- Spam emails continued to be correctly routed to Junk folders
- Reduced recurrence of known repeated spam senders
- No disruption to legitimate inbound business emails
- Improved client understanding of email filtering behaviour and limitations

---

## Demo Video
An unlisted short time-lapse video demonstrating the spam filtering process in cPanel is available below.  
The video has been intentionally blurred to protect client privacy and sensitive information.

🔗 **YouTube link:**  
(https://youtube.com/shorts/pbVFSs2FSOg?feature=share)

---

## Key Learnings
- Importance of reviewing existing global filters before adding new rules
- Risks associated with over-filtering business email environments
- Value of targeted blacklist rules over broad blocking
- Differences in spam handling across email clients
- Importance of balancing security with usability

---

## Notes
- This project reflects real ICT support work performed in a managed services environment.
- No client-identifying information is included.

---

## License
This project is licensed under the MIT License.
