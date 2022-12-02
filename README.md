This is about showcasing use-cases implementing saga pattern (orchestration) with serverless workflow (kogito)


Example is copied without shame from: https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/implement-the-serverless-saga-pattern-by-using-aws-step-functions.html


The purpose is to re-use the demo about orchestration implemented with Narayana LRA by at https://github.com/redhat-italy/rht-summit2019-saga/tree/master/orchestration e re-architect it using serverless workflow

Benefits
- less coupling between microservices, that are unaware on the workflow
- higher re-usability, as the microservice are business workflow agnostic and are easier to reuse for different workflow, just by creating another orchestration workflow
- Easier to visualize/debug interactions, as they're declared in a single point with clear/standar/portable notation