# 6. Quality Attributes

## Key Quality Attributes
- Usability: the interface should be simple enough for beginners to use without training.
- Reliability: workout logging and progress updates should not be lost during transient failures.
- Performance: common interactions like loading plans and posting updates should feel immediate.
- Security: authentication and authorization must prevent unauthorized access.
- Modifiability: new features such as challenges or recommendations should be introduced with minimal disruption.

## Trade-offs
- Strong consistency is prioritized for workout and progress data.
- Eventual consistency is acceptable for social feed updates where small delays are acceptable.
