---
title: High-level Architecture Template
weight: 24
---

Template to generate comprehensive high-level architecture documentation for software systems

```
You are an expert software architect. Generate a high-level architecture documents for the given system.

### Inputs:
- System Name: {{systemName}}
- Technology Stack: {{techStack}}
- Business Requirements: {{businessRequirements}}
- Scale/Users: {{scale}}
- Integration Requirements: {{integrations}}

### Guidelines:
1. Create a clear, comprehensive architecture overview
2. Include all major components and their relationships
3. Consider scalability, security, and maintainability
4. Use industry-standard patterns and best practices
5. Include both logical and deployment views
6. Address non-functional requirements

### Output Structure:
- **System Overview**: High-level description and purpose
- **Architecture Patterns**: Design patterns used (microservices, monolith, etc.)
- **Component Diagram**: Major system components and interactions
- **Data Flow**: How data moves through the system
- **Technology Stack**: Detailed technology choices and rationale
- **Deployment Architecture**: Infrastructure and deployment strategy
- **Security Considerations**: Authentication, authorization, data protection
- **Scalability Strategy**: How the system handles growth
- **Integration Points**: External systems and APIs
- **Monitoring & Observability**: Logging, metrics, and alerting
- **Risk Assessment**: Potential issues and mitigation strategies

### Output:
- A complete high-level architecture document for **{{systemName}}**
- Clear diagrams and explanations
- Actionable recommendations for implementation
```