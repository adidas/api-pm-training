# Module 9 - Retirement - Instructor

## API deprecation, phase-out and retirement

Phasing out old functionality or the entire API is one of the hardest challenges only to be matched by the continuously evolving the API without breaking any client. Except, this time, you might be breaking some clients. In this module students are asked to partially retire an API. Identified endpoints need to be marked deprecated and eventually phased out.

## Expected Outcome

The students are expected to prepare a plan to remove the functionality as follows.

### Verify the validity of the retirement request (Strategy & Roadmap)

Double check with the business, engineering and reporting results what functionality should or needs to be removed. Challenge The Boss if necessary because the 5% traffic could be the most valuable one.

### Identify the impact of the retirement (Strategy & Roadmap)

What clients will be affected? Can you reach out to them? What is the business, costs and operation impact? Are there alternative solutions to removed functionality? What is the upgrade / migration path for affected users?

### Prepare the phase out strategy (Development & Runtime, Documentation)

How is the functionality going to be removed? How much time is needed versus requested for the phase-out?

Example of the phase-out roadmap:

1.  Prepare the migration path from the old functionality
2.  Decide on the timeline
3.  Communicate the phase-out to clients
4.  Mark the endpoints as deprecated
    1.  in the product specification (API description)
    2.  in the documentation
    3.  at runtime ([https://goodapi.co/insights/deprecation-and-sunsetting](https://goodapi.co/insights/deprecation-and-sunsetting))
5.  Remove the endpoints from the (new) user-facing documentation, so that clients will no longer use the endpoints being removed
6.  Urge clients using the deprecated functionality to migrate
7.  Repeat step 6, make sure to understand and cater for they needs
8.  Talk to any remaining users and try to get their commitment to migrate
9.  After a final notice, if possible, take the endpoints offline
10.  Setup redirects at least to the documentation / deprecation notice

Adidas API Guidelines provide further reading on how to retire an API [https://adidas.gitbook.io/api-guidelines/rest-api-guidelines/evolution/phasing-out-old-versions](https://adidas.gitbook.io/api-guidelines/rest-api-guidelines/evolution/phasing-out-old-versions).

### Hard switch-offs (Strategy & Roadmap)

As a product owner, responsible for the product success, you are responsible for migrating the existing clients out of the old functionality. It is possible to "hard switch-off" few remaining users that refuse the migrate or are not responding but be prepared for a negative PR that might go as far as affecting your position on the market or breaking the trust of engineers. If possible, avoid hard "switch-offs" in favor of migration or hidden retirement.

### Hidden retirement (Strategy & Roadmap)

Note, sometimes it is preferable to not take the old functionality completely out for its existing users. If this is needed, the old version might be maintained in parallel and available only to the original customers. Newer versions of the API will not have the retired functionality. The retired functionality will not be accessible to new users. This needs to be accounted for by the infrastructure and as such is best to be planned at the inception of the product. Feature switches are one of the possible approach how to handle hidden retirements.
