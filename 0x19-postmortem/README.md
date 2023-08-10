INCIDENT DURATION
(12:00 p.m. to 2:00 p.m. EAT) Impact: Potential purchases were lost as a result of users being unable to reach the checkout page on our e-commerce website. 20% of users were impacted, roughly.
CAUSE OF INCIDENT: The checkout page crashed occasionally after a recent update to the website's payment gateway integration exposed an issue.


TIMELINE OF INCIDENT
At 12:00PM - , our monitoring system alerted us to a spike in 500 failures on the checkout page, which relates to how the problem was originally discovered.
At 12:05PM - The engineering team was alerted to the problem and started looking into it.
At 12:10PM - Initial analyses indicated that the problem was associated with the website's database, so the team started looking at the database logs and doing database queries to pinpoint the issue.
At 12:20PM - The team started looking at the payment gateway logs and code after further research indicated that the problem was really connected to the integration of the payment gateway.
At 12:40PM - After further research established that the problem truly connected to the payment gateway integration, the team started looking at the payment gateway logs and code.
At 1:00PM - Senior engineers and the supplier of the payment gateway were notified of the situation.
At 1:30PM - To create and put into action a fix for the problem, the team collaborated with the supplier of the payment gateway.
At 2:00PM - Users may now access the checkout page after the problem has been fixed.


UNDERLYING ISSUE AND RESOLUTION
A flaw in the integration code for the website's payment gateway was the main source of the problem. The fault specifically caused the checkout page to crash when customers tried to use a specific credit card type.

The problem was fixed once the technical team and the supplier of the payment gateway found and fixed the integration code flaw. Fixing the issue entailed rewriting the code to correctly handle the faulty credit card type and making sure that similar flaws wouldn't be added in further releases.

CORRECTIONAL AND PREVENTIVE MEASURES
The engineering team has put many remedial and preventative procedures in place to ensure that situations like this don't happen again, such as:

reviewing each integration with a payment gateway in detail to make sure it is working correctly and is not prone to the same errors. putting in place more stringent testing techniques for website and integration changes. enhancing monitoring and warning systems to recognize and address comparable problems sooner in the future. Creating and preserving incident response guidelines will help to guarantee that problems are escalated and fixed as fast and effectively as feasible.

EFFORTS TO SOLVE THE PROBLEM

To make sure the payment gateway integration code is operating properly, review and update it. Create and put into use new testing protocols for website integrations and upgrades. Update monitoring and warning systems to more rapidly identify and address similar problems. Create and maintain incident response guidelines to make sure problems are fixed as quickly as feasible.


