# Examples Guide

This guide shows how raw data should be transformed into the desired output format using the `interview-to-jtbd` skill.

## Example 1: Raw Interview Data

**Input Transcript Excerpt (Participant: Sarah, Freelance Designer):**
> "Honestly, the hardest part of my month is invoicing. I use Excel right now. I have this template, but every time I get a new client, I have to manually duplicate it, change the address, look up my time tracking app, and copy the hours over. Last week I messed up a formula and undercharged a client by $200. It's so stressful. I just want to send a professional looking PDF without spending 3 hours on a Sunday doing math."

## Bad AI Output (What NOT to do)

**Invoicing Feature Request**
Sarah needs an invoicing feature built into the time tracking app. It should automatically generate PDFs and calculate math so she doesn't lose money.
*(Why this is bad: It jumps straight to a solution, ignores the emotional context, and doesn't frame the core need).*

## Good AI Output (Applying the Skill)

**JTBD Map Extraction**

## Job: Manage Client Billing
**Statement:** When it is time to bill a client for completed work, I want to quickly generate an accurate, professional invoice so I can get paid correctly without wasting personal time.
**Evidence:**
- > "I just want to send a professional looking PDF without spending 3 hours on a Sunday doing math." (Sarah)
- > "Last week I messed up a formula and undercharged a client by $200. It's so stressful." (Sarah)
**Current Workaround:** Manual Excel templates and copying data from a separate time-tracking app.

**Opportunity Area**

## Opportunity: Eliminate Manual Data Entry in Billing
**Related Job:** Manage Client Billing
**The Unmet Need:** Moving data from time-tracking to invoicing is manual and error-prone, causing financial loss and stress.
**Severity/Importance:** High (Direct financial impact and high emotional stress).
**Evidence:**
- Sarah lost $200 due to a manual formula error in her workaround.
