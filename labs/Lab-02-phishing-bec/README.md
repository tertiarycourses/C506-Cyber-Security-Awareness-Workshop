# Lab-02: Detect Phishing and Business Email Compromise

**Course:** Cyber Security Awareness Workshop  
**Course code:** C506  
**Time:** 35 minutes  
**Alignment:** LO1, LO3  
**Tool:** [Cybersecurity Simulator + Regex Generator](https://alfredang.github.io/regexgenerator/)

## Scenario

Accounts staff must detect a lookalike supplier domain before approving a high-value transfer.

## Safety and authorisation boundary

- Use only the named training tool and the mock files in this folder.
- Do not enter real passwords, personal data, payment details or confidential information.
- Do not test any other website, network, account or organisation.
- Stop immediately if the target, data or behaviour differs from the written scope.
- Prefer reversible actions and preserve synthetic evidence.

## Mock data

- `mock-inbox.csv`
- `mock-approved-domains.csv`

## Detailed procedure

1. Compare each sender domain in mock-inbox.csv with the approved supplier domains; inspect every character.
2. Mark persuasion cues such as urgency, authority, secrecy, changed payment details and unusual attachments.
3. Use Regex Generator to create a pattern that flags the supplied lookalike-domain examples without matching the approved domains.
4. Test the expression on every sample; record true positives, false positives and false negatives.
5. Draft a safe verification message and a call-back procedure that uses a previously known contact channel.
6. Decide which emails require immediate escalation and name the recipient role, urgency and evidence to include.

## Completion standard

- Annotated inbox
- Tested regex
- Detection test results
- Independent verification script
- Escalation decision

## Reflection

What evidence would make you reverse your decision, and who would need to know?
