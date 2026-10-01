# Lab-08: Triage Suspicious Network Traffic

**Course:** Cyber Security Awareness Workshop  
**Course code:** C506  
**Time:** 35 minutes  
**Alignment:** LO1, LO3  
**Tool:** [PCAP Analyzer](https://alfredang.github.io/pcapanalyzer/)

## Scenario

A workstation generates unusual DNS and outbound traffic after a user opens an attachment.

## Safety and authorisation boundary

- Use only the named training tool and the mock files in this folder.
- Do not enter real passwords, personal data, payment details or confidential information.
- Do not test any other website, network, account or organisation.
- Stop immediately if the target, data or behaviour differs from the written scope.
- Prefer reversible actions and preserve synthetic evidence.

## Mock data

- `mock-traffic.pcap`
- `mock-packet-summary.csv`
- `mock-known-services.csv`

## Detailed procedure

1. Upload only the supplied synthetic mock-traffic.pcap to the PCAP Analyzer; do not upload production captures.
2. Identify top talkers, unusual ports, repeated destinations, DNS lookups and cleartext indicators.
3. Correlate packet observations with mock-packet-summary.csv and mark any disagreement.
4. Build a five-event timeline and identify the earliest reliable sign of compromise.
5. Decide whether to monitor, block, isolate or escalate; include potential business impact.
6. Write an evidence-preserving handover note without including unnecessary personal data.

## Completion standard

- Traffic findings
- Five-event timeline
- Earliest reliable signal
- Containment decision
- Handover note

## Reflection

What evidence would make you reverse your decision, and who would need to know?
