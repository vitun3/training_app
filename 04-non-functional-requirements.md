# 4. Non-Functional Requirements

## Quality Attributes
- Availability: 99.9% monthly uptime for core user flows.
- Performance: API responses for primary actions under 500 ms p95 in normal load.
- Scalability: support up to 100k concurrent active users over time.
- Security: protect user data with encryption in transit and at rest.
- Reliability: recover from component failures without data loss.
- Maintainability: separate application concerns to enable independent evolution.

## Constraints
- The solution should be deployable on a cloud platform with managed databases and container orchestration.
- The system must support continuous integration and delivery.
- Source code should be versioned and follow secure development practices.
