# Module 3 - First Product Iteration - Instructor

In the "First Product Iteration," the students are tasked to take the product from verified API description and non-functional requirements to its first realisation.

## Expected Outcome

The expected output is a minimal viable product handed over to the first group of selected users in a controlled launch.

### Work with the Developers (Development & Runtime)
One of the most critical aspects of a great product owner is her ability to work with the team. The product owner must make herself available during the development for the engineering. She must work with the team to quickly clarify any uncertainties and answer questions about the product specifications, non-functional requirements, or other considerations.

Developers may find discrepancies or errors which need the product owner to amend the product requirements or reconsider the non-functional specifications. In which case, the product owner must not skip the (re)verification with every stakeholder.

### API Management (Development & Runtime)
Considering the product go-live strategy from the previous module, the product owner should prepare the target API gateway or management for the initial exposure to the user. This step might include setting up the API management product plans, quotas, rate limits, or access tiers. Besides, the API product owner should also set the initial product measurements.
The Product Manager might ask the API platform team for assistance in configuring the API Gateway or Management.

### Basics of API Portal / Documentation (Documentation)
The first release should also include proper API documentation. Depending on the product go-live strategy set in module two, the documentation will be published on an API portal or elsewhere. The documentation consists of:

1. Introduction
1. What can I do with the API?
1. Description of the typical use-cases
1. API relation types (for REST APIs)
1. API vocabulary
1. Description of the individual resources (for REST APIs) and operations
1. Description of the used non-standard media types

See the "API Documentation Template"  [https://tools.adidas-group.com/confluence/display/DIDA/API+Documentation+Template](https://tools.adidas-group.com/confluence/display/DIDA/API+Documentation+Template)

### Verify that the Product Matches the Contract (Development & Runtime)

Before going live, the product owner must make sure the implementation matches the approved API description – contract.

The product owner can do the verification manually. However, it is recommended to use an automated testing framework like Dredd to verify the compliance with contract and additional integration tests to confirm any end-to-end scenarios.

See the "REST API Specification Lifecycle and Validation"  [https://tools.adidas-group.com/confluence/pages/viewpage.action?pageId=346837802](https://tools.adidas-group.com/confluence/pages/viewpage.action?pageId=346837802)  for more details.

The product owner should work with the developers to set the tests in an automated fashion alongside the development lifecycle.

### Hand Over to Selected Clients (Development & Runtime)

With the MVP implement, deployed, verified, documented and published, the product owner is expected to reach out to its first users.

The product owner should identify suitable clients for the initial rollout phase. The product owner may assist users during their first interaction with the API, considering their input for the further refinements of the product.
