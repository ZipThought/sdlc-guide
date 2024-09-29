# Timeframes and Milestones in OKR-Based SDLC

This document outlines how timeframes and milestones are structured in our OKR-based Software Development Life Cycle (SDLC), focusing on full-stack software engineering with emphasis on both frontend and backend development.

## OKR Layers

Our SDLC uses a three-layered OKR model:

1. **Product OKRs**: Set the overall direction for the product.
2. **Team OKRs**: Align with Product OKRs and define team-specific goals.
3. **Individual OKRs**: Derive from Team OKRs and focus on personal contributions.

## Timeframe Structure

We typically operate on a quarterly cycle:

- **Week 1-2**: OKR setting and alignment at all levels
- **Weeks 3-11**: Development sprints (2-week cycles)
- **Week 12-13**: Quarter-end review and next quarter planning

## Example: 3-Month Full-Stack Development Cycle

Let's walk through an example to illustrate how multiple objectives at each OKR layer work together over a quarter in a full-stack development context.

### Product OKRs

**Objective 1: Enhance platform scalability and performance**
- KR1: Increase system throughput by 50% to handle 100,000 concurrent users
- KR2: Reduce average API response time to under 100ms
- KR3: Achieve 99.99% uptime across all services

**Objective 2: Improve user engagement and retention**
- KR1: Increase Daily Active Users (DAU) by 20%
- KR2: Reduce user churn rate by 15%
- KR3: Increase feature adoption rate of new users by 25%

### Team OKRs (Full-Stack Development Team)

**Objective 1: Optimize backend infrastructure and services**
- KR1: Implement horizontal scaling for key microservices
- KR2: Optimize database queries to reduce average query time by 40%
- KR3: Implement comprehensive error handling and logging across all services

**Objective 2: Enhance frontend performance and user experience**
- KR1: Improve initial page load time by 30% across all devices
- KR2: Implement progressive loading for main application features
- KR3: Achieve 95% test coverage for critical frontend components

### Individual OKRs (Backend Engineer)

**Objective 1: Improve database performance and reliability**
- KR1: Implement database sharding for high-traffic tables
- KR2: Optimize top 10 most resource-intensive database queries
- KR3: Implement and test automated failover for database clusters

**Objective 2: Enhance API security and performance**
- KR1: Implement rate limiting and throttling for all public APIs
- KR2: Reduce API authentication overhead by 25%
- KR3: Develop and document secure API endpoints for new features

## Milestones and Timeframe

Weeks 1-2:
- Set and align multiple OKRs at all levels
- Product team defines metrics for tracking all OKRs
- Teams break down OKRs into specific tasks and projects

Weeks 3-4 (Sprint 1):
- Product: Begin tracking system throughput and API response times
- Full-Stack Team: Start backend performance audit and frontend load time analysis
- Backend Engineer: Begin database performance analysis and API security audit

Weeks 5-6 (Sprint 2):
- Product: Review initial performance audit results and user engagement metrics
- Full-Stack Team: Begin implementing horizontal scaling and start frontend optimization
- Backend Engineer: Start implementing database sharding and API rate limiting

Weeks 7-8 (Sprint 3):
- Product: Mid-quarter OKR progress review across all objectives
- Full-Stack Team: Continue backend optimizations and implement progressive loading on frontend
- Backend Engineer: Optimize critical database queries and enhance API authentication

Weeks 9-10 (Sprint 4):
- Product: Analyze impact on system performance and user engagement
- Full-Stack Team: Implement error handling framework and increase frontend test coverage
- Backend Engineer: Set up database failover mechanism and develop new secure API endpoints

Week 11 (Sprint 5):
- Product: Prepare for major backend and frontend updates rollout
- Full-Stack Team: Final testing and optimization of all implemented features
- Backend Engineer: Comprehensive testing of database and API improvements

Weeks 12-13:
- Deploy major system updates
- Conduct end-of-quarter review
- Evaluate OKR achievement at all levels across all objectives
- Begin planning for next quarter

Throughout this process, higher-level OKRs guide the creation of lower-level OKRs, ensuring alignment across the organization. Regular check-ins allow for adjustments, considering progress across multiple objectives and both frontend and backend aspects of development.

## Adapting to Different Project Sizes

- **Shorter Projects** (1-2 months): May focus on critical backend improvements or specific frontend features, aligning closely with immediate Product OKRs.
- **Longer Projects** (6+ months): May involve major architectural changes, database migrations, or comprehensive frontend rewrites. OKRs would be adjusted quarterly while maintaining focus on long-term goals.
- **Plan Enough**: While there is tendency to minimize planning, research show that most of successful projects use about 25% time for planning [[1]](#references), above 15% commonly reported. Hence, we should aim to use between 15% time for OKR setting and expect about 10% spread out during the execution, e.g. sprint planning.

Remember, this structure is flexible and should be adapted to suit the specific needs of each project. The key is maintaining a balance between frontend and backend development while ensuring all layers of OKRs remain aligned.

## References
[1] P. Serrador and R. Turner, “What is Enough Planning? Results From a Global Quantitative Study,” IEEE Trans. Eng. Manage., vol. 62, no. 4, pp. 462–474, Nov. 2015, doi: [10.1109/TEM.2015.2448059](https://doi.org/10.1109/TEM.2015.2448059).