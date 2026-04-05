# Human-Resource-Analysis-on-Excel
This HR Dashboard provides a holistic view of an organisation's human resources landscape. It covers 50 total employees across five departments — Finance, HR, IT, Marketing, and Operations, and tracks workforce demographics, skill distribution, compensation, leave patterns, employment status, and geographic distribution of staff.

![HR Image](https://uk.morganphilips.com/Portals/2/EasyDNNNews/398/images/img-shutterstock_HR-2-600-600-p-L-97.jpg)

 Source: Kaggle

## Data Cleaning Steps and Processes 
1. Standardisation of job titles — Role names like "HR Specialist", "Developer", "Designer", were normalised to remove duplicates or inconsistent spellings before aggregating salary and leave data.
2. Gender encoding — Gender values were reduced to binary Male/Female categories and converted to percentages for the donut charts. All null or non-standard were excluded.
3. Age banding or grouping — The ages were extracted from the date of birth and the ages were grouped into five uniform bands: 18–25, 26–35, 36–45, 46–55, and 56+, enabling the grouped bar chart comparison.
4. Salary aggregation — Salary figures per employee were summed by job title to produce the total salary by role table. 
5. Leave data consolidation — Leave records were summed per job title to produce the "Leaving Tracking" bar chart. 
6. Employment status categorisation — Employment types were tagged into three buckets: full-time, part-time, and contract, then counted.


## Key Performance Indicators (KPIs)
**Workforce size:** 50 total employees — 48% male, 52% female.
**Average age rating:** suggesting a relatively young workforce.
**Salary totals by role:**

HR Specialist — highest at ₦959,266

Developer — ₦633,842

Designer — ₦613,842

Manager — ₦731,170

Analyst — ₦167,041 (lowest)

## Employment type:

Full-time employees: 13

Part-time employees: 17

Employees with contracts: 20

## Work location split:

**Branch Office:** 46%

**Remote:** 38%

**Head Office:** 16%

## Skills distribution:

Communication (12) and Management (11) and Design (11) are the top skills, followed by Python (9) and Excel (7).

## Leave usage by job title:

**Manager:** 123 days

**HR Specialist:** 110 days

**Designer:** 104 days

**Analyst:** 28 days (lowest)

## Observation 
**Analyst compensation is extremely low**
At ₦167,041, analysts earn roughly 5–6× less than HR Specialists. This disparity may cause retention issues at entry level.

**Contract workers dominate headcount**
20 of 50 employees are on contracts, with only 13 full-time. Over 60% of the workforce lacks permanent status, suggesting workforce instability.

**Near gender balance achieved**
52% female vs 48% male — a near-equal split that reflects inclusive hiring. Most age groups also show balanced gender representation.

**Managers take the most leave**
Managers logged 123 leave days, highest of any role. This may indicate burnout risk or generous leave entitlements for senior staff.

**Remote work is significant**
38% of staff work remotely — nearly as many as the Branch Office (46%). Only 16% are at Head Office.

**Central region leads headcount**
Central has 14 employees, outpacing East (10), South (10), North (7), and West (9). Regional HR strategies may need tailoring.

**Technical skills are underrepresented**
Excel (7) and Python (9) are the lowest-counted skills. In a data-driven environment, this could limit analytical capability across departments.

**Young workforce concentrated in 26–35**
The 26–35 age bracket is the largest, with 7 males and 6 females. The 56+ group is the smallest, suggesting limited senior workforce retention.

## Conclusion
The organisation has a relatively small but diverse workforce of 50 employees. Gender representation is well-balanced. However, the workforce structure is fragile, majority of staff are either part-time or on temporary contracts, with only 13 permanent full-time employees. Salary distribution is highly uneven, particularly disadvantaging analysts. The predominance of remote and branch-based working suggests reduced Head Office presence, which may affect team cohesion and management oversight. The age profile skews young (peak at 26–35), which is positive for long-term capacity but raises questions about knowledge retention as the 56+ group is minimal. The Central region has the most employees, pointing to geographic concentration of operations.


## Recommendations
1. Address the analyst pay gap urgently. The ₦167,041 total for analysts is disproportionately low. A compensation review should benchmark analyst salaries against market rates to reduce attrition risk at the entry level, which is typically a feeder pool for senior roles.
2. Convert contract and part-time staff strategically. With 37 out of 50 employees in non-permanent roles, the organisation is heavily reliant on flexible labour. Identify high-performing contract staff for full-time conversion to build institutional knowledge and loyalty.
3. Invest in technical upskilling. Excel and Python are the least represented skills. Running structured training programmes in these areas would strengthen the organisation's analytical and automation capabilities across departments.
4. Monitor manager burnout proactively. Managers logged the highest leave days (123). While some leave is healthy, HR should conduct regular wellbeing check-ins and assess whether managerial workloads are sustainable, particularly with a large remote workforce to oversee.
5. Develop a regional HR strategy. The imbalance across regions (Central at 14 vs North at 7) suggests uneven distribution of resources and talent. A regionalised recruitment or deployment plan could balance capacity across all five regions.
6. Strengthen the senior workforce pipeline. The 56+ age cohort is the smallest in the organisation. Succession planning, mentorship programmes, and targeted retention strategies for experienced employees would protect institutional knowledge from being lost as older staff eventually exit.
