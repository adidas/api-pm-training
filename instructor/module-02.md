# Module 2 - Product Specification - Instructor

Students continue working on the Voucher API. They have already articulated the requirements, identified the use cases, and formulated hypotheses in the previous module (one).
In this module, they are tasked to refine the use-cases into a product specification and a plan on execution.

## Expected Outcome

The core outcome should be a product specification in the form of a testable API description and non-functional requirements. The design should be verified, and once approved, it should serve as the basis for contract-driven development.
Besides, the product owner should cover standard aspects of the product inception.

### Develop API Contract (Specification design)
An (API) architect should be called upon to decide what architectural style/s or paradigm/s to use (e.g., REST, GraphQL, Kafka ...). Also, the architect is responsible for the definition of the internal systems architecture and providing feedback on the feasibility and costs of the solution.
The outcome should be an API description file formalising the design, which fulfils the projected use-cases. An architect can partly author the API description. However, the product owner must be able to read and modify the API description, in particular, the human-readable elements (e.g., operation descriptions).

### Validate the design with API guidelines (Specification design)
The API description is expected to follow the API guidelines. By having harmonised guidelines we make sure that all APIs "look like they have been developed by the same person" which will contribute to provide a consistent and predictable experience for the developers that will develop against the API.

### Validate the design with stakeholders (Specification design)
The design, as captured in the API description, should be validated with the expected client applications. Ideally, each stakeholder has the chance to look at the design, interact with the mock service, and provide the feedback.
The product owner (or architect) should reflect the feedback in the API description, either altering the design or clarifying the descriptions.
Mocking is a fundamental part of this step. The product owner should be familiar with API mocking and use it for quick prototyping and design feedback.

### Define non-functional requirements (Development & Runtime)
Based on client applications requirements, the product owner should specify any non-functional requirements of the product — for example, the SLAs, rate limits, geographical availability, etc.

### Consider security implications (Specification design)
Security considerations should accompany the product specification. Is the API public to everyone on the network? What are the restrictions on resources or operations and to whom? How do you handle identity with regards to existing organisational identity services? What about data privacy, GDPR, or other regulations?

### Come with the initial go-live strategy (Strategy & Roadmap)
This part covers how the API is published and consumed. The product owner should have a strategy for how the API is released.
When (what is the timeline) and where will be the API release? Will it be exposed through organisational API management? If so, which one and how (API management products, plans)?
Is the API listed only in the internal API repository or will it be listed on API Portal?
How do you notify the intended and potential users? How is the API supported and marketed?

### Prepare cost projects, weight costs versus expected benefits (Strategy & Roadmap)
The product owner should decide where to make investments (documentation, support, runtime) and based on what. As part of the product preparation, the product owner should estimate the costs based on the product specifications and product strategy and pit the cost estimates against the expected benefits of the API product.

### Prepare the roadmap – priority backlog (Strategy & Roadmap)
The first product iteration cannot meet every product feature or non-functional requirement. What is the minimal viable product? What are the priority features, and what is the roadmap for delivery?
