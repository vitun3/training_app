# 12. Deployment View

## Deployment Topology
- A load balancer fronts the web application and API gateway.
- The application is deployed as containerized services in a managed Kubernetes cluster.
- A managed PostgreSQL database stores core transactional data.
- Redis is used for caching and temporary state.
- Object storage holds media files and exported content.

## Operational Concerns
- Use health checks, autoscaling, and rolling deployments.
- Collect logs and metrics centrally for observability.
- Separate production and staging environments.
