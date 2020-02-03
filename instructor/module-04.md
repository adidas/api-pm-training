# Module 4 - Go Live - Instructor

The moment of go live has arrived. There are some preparations that need to be taken care of before going live. Those activities are mainly focused on making sure we will be able to monitor the activity and support our clients within the framework of a Service Level Agreement. In addition a proper communication plan for go live needs to be put in place.

Students may challenge the approach suggested by the boss of going live for all teams after delivering the API to a first round of selected clients. A phased approach of releasing the API to a increasing number of clients is a valid practice as well.

## Expected Outcome

### Monitoring and KPIs (Development and Runtime)
Monitoring tools need to be in place in order to make sure that the product is

1.  behaving as expected
2.  data is available in case of incidents

KPIs have to be defined as well so that we can improve the product going forward based on the insights provided. Interesting KPIs are:

-   availability
-   performance
-   number of client applications
-   number of requests

### Operations setup (Development and Runtime)
Incidents and problems (ITIL) will happen. We need to setup the process by which we are going to handle operations. Top concerns here are:

-   What are our Service Level Indicators (SLI) and Service Level Objectives (SLO)?
-   How do we manage incidents?
-   How do we manage critical incidents and escalations, and what roles are involved?
-   How do we communicate with client applications in those circumstances?
-   How do we organize on-call rotations?
-   How do we manage alerting?
-   How do we manage post-mortems?
-   What communication channel are going to make available (Q&A forums, chat, bug tracking...)?
-   How are we going to measure our performance?
    -   Mean time to reaction
    -   SRE Budget
    -   Number of incidents and their criticality

### SLA agreements (Support)
A Service Level Agreement is an explicit contract with your users that includes consequences of meeting (or missing) the SLOs they contain. SLAs need to be agreed with the community of clients that will use the API.

### Go-live communication preparation (Support)
Letting potential clients know that an API is ready for consumption is a key activity during the go-live process. Those are some elements to consider:

 - Let clients know when will the API be released.
 - Decide on the API management and plans to apply and let clients know how to gain access to the API.
 - Communicate what channels of communication are available to them to get support.

### Economics (Strategy & Roadmap)
In the previous module, we made the API available to selected consumer applications. That is the first step towards realizing its strategic value. But this is only a _potential_ value, not an actual one. At this stage, we want to fully realize its value - be it monetary or some other qualitative benefit. We need to be prepared to gather the evidence that will validate the hypothesis previously stated in module 1.
