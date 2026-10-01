# Lab-09 Checklist

## Before

- [ ] I am using only supplied mock data.
- [ ] I confirmed the tool URL and training scope.
- [ ] I will stop if the environment differs from the instructions.

## During

- [ ] Step 1: Read the detection requirements and label the supplied log lines as expected match or expected non-match.
- [ ] Step 2: Use Regex Generator to build a pattern for failed-login lines while capturing timestamp, username and source IP.
- [ ] Step 3: Test every line and calculate true positives, false positives and false negatives.
- [ ] Step 4: Refine the expression to reduce noise without excluding the malicious samples.
- [ ] Step 5: Define a threshold and time window for escalation; explain the cost of a threshold that is too low or too high.
- [ ] Step 6: Document the rule purpose, assumptions, limitations, owner and review date.

## Before submission

- [ ] Tested regex
- [ ] Confusion matrix
- [ ] Threshold decision
- [ ] Rule documentation
- [ ] Escalation criteria
- [ ] Screenshots are redacted and contain no real personal or secret data.
- [ ] My conclusion distinguishes fact from inference.
