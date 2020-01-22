# Module 6 - Strange usage patterns - Instructor

In this instalment, the attendees were tasked to look into odd usage patterns in the monitoring. The unexpected way of using the API is causing technical issues to the backend team as the database is not optimized for such use. Besides, the way the users call the API might not be the optimal workflow for effectively using the vouchers, issuing new ones, and preventing the issued vouchers from re-use.

## Expected Outcome

When users are consuming the API in an unexpected way, it can be interpreted as a bad design but also an opportunity to discover new market and use-cases.

### Challenge current status (Strategy & Roadmap)

The students should reconsider the results from the first four modules (business challenge, product specification, and implementation), similar to the previous module (Poor NPS); this would include:

-   Challenge the original use-cases
-   Challenge the original product specification
-   Challenge the original product-market-fit
-   Challenge the API design
-   Challenge the documentation
-   Challenge the technical implementation

First, it is needed to discover what users are doing with the API and why they are doing it in a way that we did not predict initially? Is this because of some technical problems or just poor documentation, leading to a lack of understanding? Or is the problem more rooted in the design of the API? Finally, are the hypotheses about the use-cases, business value, and target audience correct?

The students should also reach out to API consumers to verify whether the original use-cases are still valid. Only then, students can propose the solution.

### Fix according to findings (Strategy & Roadmap)

Based on the findings, the students might propose fixing the documentation or working with developers to fix the technical issues.

Changes in design would take us back to the (re)development of the contract and its validation with stakeholders.

Finally, if the root of the problem is in the wrong hypotheses about the use-cases or the target market (audience), the product specifications will have to be reviewed.

### Setup monitoring to detect unexpected behavior (Development & Runtime)

To discover the reasons for the strange behavior, students should work with the operations and development team. Understand well the API monitoring and the critical architectural constraints of API implementation.

Note: Proposal to leave the API as is, only alter the initial use-cases to match the actual use of the API might also be a valid output.
