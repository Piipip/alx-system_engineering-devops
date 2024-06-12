# Postmortem
Learning how to write an Incident Report, also referred to as a Postmortem. This postmortem follows the guidelines used closely by google engineers to file reports. The report is made up of five parts, an issue summary, timeline Root cause analysis Resolution and Recovery Corrective and Preventive measures. Lets review each of these parts in detail.
## Issue Summary:

* Consider adding the affected service or system name for clarity.

## Timeline:

* Include key milestones during the incident, not just actions or events. Examples could be reaching critical failure thresholds, isolating the issue, deploying a fix.
* Mention the time zone at the beginning of the report, not repeatedly in the timeline.

## Root Cause Analysis:

* You can break this down further. Briefly explain what happened (technical details), then analyze why it happened (underlying factors). 
* Include any data or logs that support the root cause. 

## Resolution and Recovery:

* Specify who took the actions and their roles (e.g., engineer on duty, response team).
*  If there were rollbacks or data recovery involved, mention them here.

## Corrective and Preventative Measures:

* Prioritize these actions.  
* Consider both short-term fixes and long-term improvements to infrastructure or processes.

