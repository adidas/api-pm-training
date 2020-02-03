# Module 7 - API Evolution - Instructor

Evolving an API is a challenge that any non-trivial API will face at some point of its lifetime. While doing so, it is essential that current clients don't face any negative consequences. The topic of API versioning will surface at this stage. It is one of the most controversial topics in API management and it is a good practice to keep it in mind from the very beginning of the API design. To that end, the adidas API guidelines provide some rules for extending: [https://adidas.gitbook.io/api-guidelines/general-guidelines/rules-for-extending](https://adidas.gitbook.io/api-guidelines/general-guidelines/rules-for-extending).

Do your best to not disturb existing clients. Some of them may be interested in the new features, others may be just fine with the current status, or simply they lack the budget and resources to accommodate interesting changes.

## Expected Outcome

The expected outcome is a plan and the corresponding activities to evolve the API contract without impacting existing clients.
Extending an API should take into account the following aspects:

### Identify who is impacted
With the help of the monitoring and API gateway tooling, if possible try to identify the user groups that will be impacted by the change and approach them proactively about the upcoming change.

### Provide incentives for upgrading
Upgrading to a new version almost always has a cost on the client side. Try to compensate that cost by offering incentives to upgrade, like special support plans, free API usage for a period of time (in case you are managing a paid API), etc.

### Communication to clients (Documentation)

Tell your clients that an update (a new version) is coming for the API. Explain the reasoning and changes/new features. Be very clear on what do they need to do on their end (ideally nothing) and by when.

### Update documentation and client development tools (Documentation, Development tools)

Your API portal should reflect the fact that there are two versions available, or that a transition is going to happen from the old version to the new one. Client development tools (if any) should be updated as well.

### Give clients the opportunity to test the new version (Development & Runtime)

Give client applications the opportunity to test the new version for a period of time before releasing it. Even if there are no breaking changes (as it should be), some changes may trigger bugs in client applications.

### Monitor the transition (Development and Runtime)

Prepare the monitoring tools to track the progress of migration of client applications to the new version of the API and any possible errors associated with it. Obviously, the operations team should be briefed so that they can track any incidents related to the change.
