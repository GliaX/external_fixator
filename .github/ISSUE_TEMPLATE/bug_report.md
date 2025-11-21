
**Describe the bug**
A clear and concise description of what the issue is.

**Risk Flag**: This helps the team understand the urgency of the issue and the actions to take. Select one of the following (note: RPN calculation instructions are below):

Red / High Risk – This is an urgent issue that requires us to stop production and resolve before continuing, with potential for a recall that needs to be discussed with the team immediately. This should be selected if the severity level is above 6 or the RPN is high (e.g. above 150, but this threshold is not firm yet).

Yellow / Medium Risk – This is an important issue to resolved quickly and the team should be alerted immideately, but does not require stopping production. This should be selected if the severity level is above 3 or the RPN is medium (e.g. 70-150, but this threshold is not firm yet)

Green / Low Risk – This is a minor issue to be investigated in the long-term with no major or immediate consequence to production. This should be selected if the severity level is below 3 or the RPN is low (e.g. below 70, but this threshold is not firm yet)

**Items**: Item (component, part, assembly, or process step) of the product/part with the issue.

	Example: The tip of a ball-point pen.

**Function**: Functions of an item. There can be multiple. (What is the purpose of the item / what does it do?)

	Example: Disperses ink onto paper smoothly.

**Requirement**: Requirements of a function. A requirement has one or many potential failure modes.

	Example: Delivery of proper ink amount onto paper.

**Failure Mode:** The way that an item is failing to meet the requirement. A failure mode has one or many potential effects.

	Example: Disperses too much ink.

**Effects**: Potential effects of the potential failure mode on the function and customers. There can be multiple.

	Example: Globs or drip left behind the letters.

**Severity (S):** a ranking number reflects the most severe potential effect of a failure mode. Severity ranks on a 1 to 10 scale, using the following criteria.

10 – Extremely Severe: A failure mode with this rating could cause catastrophic effects, including personal injury or death or a serious breach of safety or legal compliance. These failures usually have no prior warning and pose the highest level of risk.

9 – Very Severe: This also indicates a hazardous situation, but one where some warning is available before failure. While serious, the potential for mitigation exists, and the failure may still pose a danger to life or system operation.

7 to 8 – High: Failures at this level result in a loss of primary function or a critical system not working as intended. While not typically life-threatening, they often result in major system disruption, customer dissatisfaction, or costly downtime.

4 to 6 – Moderate: These failures involve degradation of performance or inconvenience to the user. The product may still operate, but in a diminished state. The impact is noticeable but not severe.

1 to 3 – Low: These are minor or cosmetic issues that don’t affect the functionality or safety of the product. The user might not even notice the failure, and the overall effect is negligible.

	Example: In the case of the pen, the severity is a 7 due to the failure to perform as intended.

**Cause**: The reason why failure happens. A failure mode has one or many potential causes. Can range from design flaw, process gap, human error, equipment or environmental factors. Skip if the cause is not yet known, and use the actions section below to list out next steps to investigate the cause.

	Examples:

	1. Ball diameter is too small

	2. Pressure from the user on the pen is too much.

**Prevention (Occurrence) Control:** Design action to prevent potential cause to occur. Mention the current mechanism to prevent the issue from occurring, if any.

	Examples:

	1. Study tolerance of ball diameter and its effects to line width and color.

	2. Study user’s pressure range.

**Occurrence (C):** a ranking number reflects the possibility of occurrence of the Failure. Occurrence ranks on a 1 to 10 scale, using the following criteria:

10 – Failure is inevitable.

7-9 – Failure is very likely to occur.

4-6 – Failure is likely to occur.

1-3 \- Failure is unlikely to occur.

	Example: In the case of the pen, the occurrence rate is low (scores a 3\) because the design 	will consider the normal pressure ranges and appropriate tolerances.

**Detection Control:** Design action to detect the failure or the cause of the failure if it happens. Mention the current mechanism to detect the the issue before it occurs, if any.

	Example: Writing tests with varying pressures to detect if the problem occurs.

**Detection (D):** a ranking number reflects the current detection control method. Detection ranks on a 1 to 10 scale, 10 means worst detection capability.

10 – There is no design or process control in place to detect the failure.

7-9 – Design and process controls have a low chance of detecting the failure.

4-6 – Design and process controls have a medium chance of detecting the failure.

1-3 – Design and process controls have a high chance of detecting the failure.

	Example: In the case of the pen, the controls of writing tests is very likely to detect if the 	problem occurs given a decent enough sample size to capture variances in tolerances, so it gets a score of 3.

**RPN**: (stands Risk Priority Number) An indication number to evaluate the risk of the process based on Severity, Occurrence, and Detection. Depend on RPN and S, O, D indexes, the responsible team/individual has to decide corrective action needed for each failure mode. RPN formula is: RPN \= S x O x D

	Example: For the pen, the RPN = 7 x 3 x 3 = 63

**Actions / Next Steps**:

1. Recommended next steps to investigate the failure cause e.g. trying to reproduce the failure, experiment with changing variables, mechanical tests, material analysis, discussing with suppliers, discussing with users, etc.  
2. Once the failure cause is known, propose recommended design or process improvements to reduce the risk (either by reducing the severity of the failure, reducing the occurrence rate, or improving detection). This can be a design change, process change, update to communication with users, etc.  
    	  
   1. Describe the change and what it will do to reduce the risk.  
   2. Include a validation plan for the change (e.g. tests to ensure a new process is stable or a new design is strong enough, no new issues have been generated, etc.).  
   3. Re-calculate the RPN of the updated design/process to demonstrate the improvement.

**Responsibility**: Individual person or team/department who has to complete the recommended action.

**Target Finish Date:** The planned completion date.

