# Recruiter Scam Triage

Use this when an inbound recruiter message feels plausible enough to tempt a reply but odd enough to create friction.

The goal is not to become paranoid. The goal is to avoid giving useful personal data to a thin recruiting facade.

## Case Pattern

Suspicious example, observed on 2026-05-12:

- sender presents as a named recruiter at a generic recruitment firm
- message lists many broad technical categories instead of one concrete role
- salary ranges are wide and attractive
- the call to action is to send a CV before any real role, client, hiring manager, or interview process is named
- email domain and website look superficially plausible
- public traces do not cleanly match the claimed company, phone number, address, and operating story

This pattern is common in CV harvesting, identity collection, and fake-recruiter lead funnels.

## Immediate Rule

Do not send:

- CV
- passport, visa, BRP, national ID, or Social Security number
- date of birth
- home address
- bank details
- references
- copies of certificates
- any payment, deposit, equipment fee, training fee, or background-check fee

Do not reply with `unsubscribe` if the message already looks suspicious. That confirms the mailbox is live.

## Triage Loop

### 1. Separate the claim from the evidence

Write the claim in one sentence:

> A recruiter from X says they represent real roles in Y market and wants my CV.

Then list observable evidence:

- sending domain
- visible email address
- reply-to address
- phone number
- website
- company registration name
- physical address
- LinkedIn profile
- named clients or vacancies
- message wording

If the message gives only a brand name and no verifiable operating details, treat that as missing evidence.

### 2. Check whether the company identity is coherent

Look for consistency across:

- domain name
- company name
- registered legal entity
- address
- phone number
- recruiter name
- LinkedIn company page
- job listings
- privacy policy
- email footer

One mismatch can be normal. Several mismatches are signal.

High-risk mismatches:

- domain name resembles a real company but is not the real company's domain
- website phone number differs from email phone number
- website address does not match any obvious registered company record
- LinkedIn link is missing, dead, or points nowhere
- company registration exists but is dissolved, under strike-off action, or unrelated
- the site uses generic stock content and no named staff

### 3. Inspect the recruiter request

Legitimate recruiters can be vague, but they should be able to answer basic role questions before receiving sensitive information.

Ask:

- What specific role is this for?
- Who is the client or what type of client is it?
- Is the recruiter retained, contingent, internal, or just building a candidate pool?
- What is the location, work model, seniority, and compensation band?
- What is the next step after CV review?
- What personal data will be stored, where, and for how long?

Do not send documents until the answers are coherent.

### 4. Look for pressure and data hunger

Red flags:

- "send your CV and I will shortlist roles within 24 hours"
- many unrelated role categories in one message
- very wide salary bands
- vague claims about fintechs, SaaS scale-ups, enterprise clients, or confidential openings
- no specific vacancy link
- request for ID documents early
- request to move to WhatsApp before a role is defined
- refusal to answer basic company or client questions
- urgency without evidence

The question is not "could a real recruiter write like this?" Some do.

The better question is:

> Does this person have enough verified connection to real hiring work to deserve my data?

### 5. Classify the message

Use one of four outcomes:

- **Safe enough to continue**: identity, company, role, and process are coherent.
- **Proceed with constraints**: plausible, but share only a minimal profile and ask role questions first.
- **Do not engage**: identity or process is incoherent; no reply needed.
- **Report**: message impersonates a known company, requests sensitive documents, or targets a work account.

## Minimal Reply If You Continue

If the message is not obviously malicious but still weak, use a constrained reply:

```text
Hi,

Before I share a CV, could you send the specific role description, client type, location/work model, compensation band, and your data handling policy for candidate details?

Thanks.
```

Do not include attachments in that reply.

## Evidence Note Template

```markdown
# Recruiter Triage Note

Date:
Sender:
Claimed company:
Email domain:
Website:
Phone:
Role claim:

## Evidence
- 

## Mismatches
- 

## Questions sent
- 

## Classification
Safe enough to continue / Proceed with constraints / Do not engage / Report

## Reason
- 

## Next action
- 
```

## Field Heuristic

A real recruiter relationship becomes more concrete when questioned.

A fake or low-quality funnel becomes more generic, more urgent, or more interested in documents than conversation.
