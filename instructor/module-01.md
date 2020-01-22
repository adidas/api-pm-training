
# Module 1 - The Business Challenge - Instructor

Students have been asked to collect use cases and attach an estimated business value to them.

The objective during the training is that students will work in teams and figure out WHAT and HOW they would do what they have been asked for.

## Expected Outcome
When creating a new API product it is essential to understand that multiple requirements from multiple stakeholders have to be consolidated and productised as a single product. We need to reach out to our stakeholders in order to:

### Understand the data model (Specification Design)
The data model exposed by the API has to be inclusive with the expectations of the different stakeholders. It is therefore essential to elaborate a data model that captures all pieces of information that will play a role during the lifecycle of vouchers/discounts.

### Align vocabulary (Documentation)
In close relationship with the data model, vocabulary alignment is an important step at this stage. Different stakeholders may use different vocabulary to refer to the same entity which can lead to confusion and misunderstanding. When dealing with APIs it is essential to align the vocabulary and be clear in its definitions. An aligned vocabulary should be shared with stakeholders and signed-off. This will become the vocabulary and definitions used in the API.

### Identify system landscape providing the current service (Strategy & Roadmap)
The target API will most probably rely on communicating with the systems currently providing the capabilities. You should familiarise yourself with the system landscape and identify the existing integration and process pain points. This will help you articulate business value propositions.

### Understand the business rules (Strategy & Roadmap)
The business rules around vouchers and discounts will have to be implemented in the API layer or consumed from the existing system landscape. In any case, the business rules and its consequences in terms of lifecycle, data model, state transitions, etc. must be well understood.

### Understand the user journey and its transitions (Strategy & Roadmap)
The underlying business processes for vouchers and discounts will have an impact in the style and design of the API: what steps are request/response? Which ones are event driven? What hypermedia affordances will be necessary to guide the process?

### Become familiar with current user facing applications (Strategy & Roadmap)
Our API will for sure support user interfaces, the ones that already exist and probably some more. Knowing what type of UI our API will support will have an impact on the future design of the API contract.

### Document the cost structure (in systems, KSR, development effort,...) of the current situation (Strategy & Roadmap)
To make sure our API will add value to the business we need to assess the current situation and elaborate hypothesis around the improvements the new API will bring. Therefor we need to measure the current situation to make our effort a data-driven and evidence-based one.

### Consolidate requirements via Value Proposition Canvas (Strategy & Roadmap)
Once the previous points have been collected for all stakeholders, a common technique to consolidate requirements and assess their value is to develop a Value Proposition Canvas.

### Identify use cases (Strategy & Roadmap, Documentation)
Consolidate use cases coming from different stakeholders. Merge those that are very similar or complementary. If some use cases are really different than others in terms of underlying process, vocabulary, etc. then it may be justified to build different APIs.

### Assign business value via hypothesis (Strategy & Roadmap)
Once use cases have been identified, it is time to assess the business value of each one of them. Business value may not be clear at this stage, therefor it makes sense to elaborate hypothesis based on the information at hand or other well-known market conditions. For example,

**We believe that** by offering the capability to check whether a voucher has already been used, multiple uses of the same voucher will be avoided and the margin will improve

**To verify that we will** implement the use case that allows to check whether a given voucher has already been used

**And measure if** the voucher is used more than once in all markets

**We are right if** the margin improves more than 2 million euro as this is the estimated margin improvement if we stop multiple uses of the same voucher.
