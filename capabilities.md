# Initial
- Team Empowerment (self improvement)
  - Onboard Management in Security
  - Continuously Improve
  - Participate/Found a Security Quest Guild
  - Review Capabilities/Activities
  - Risk Leadership
    - make own decisions
    - to fix or not to fix vulnerabilities
    - integration-of-vulnerability-issues-into-the-development-process

# Guild / Teamwork
- Awareness
  - simple-mob-hacking
- TODO
  - Self-improvement use "Security-Chaos-Monkey" to get challenged
    - Incentive for teams who get better (metrics)
    - ctf on other teams systems
- TODO
  - give feedback to everyone in the guild to keep everyone honest
- TODO
  - Security-Lessoned-Learned
- TODO
  - regular-advanced-mob-hacking

# Dependencies
1. Handling of Known Vulnerabilities on Request
  1. Test Server Side Libraries Regarding Known Vulnerabilities
  1. Test Client Side Libraries Regarding Known Vulnerabilities
  2. test-container-images-regarding-known-vulnerabilities
  1. test-for-default-credentials
2. Continuous Handling of Known Vulnerabilities
  - Nightly Test Components Regarding Known Vulnerabilities
3. Continuous Update of Dependencies
  - Nightly Dependency Version Upgrade
4. Usage of Well Maintained Software
  - Ensure Only Using Components Which Are Under Active Development
  - Do you regularly evaluate the lifecycle state and support status of every software asset and underlying infrastructure component

# Coding
1. SAST (Static Application Security Testing)
  - static-analysis-for-all-self-written-components (server)
  - Static analysis for important client side components
2. Code Review
  - team code-review
    - get a peer from the guild
  - guild code-review
3. Prevent Secrets in Source Code
  - prevent-secrets-in-source-code
  - Handover of confidential parameters
3. Prevent Bad Code on Commit
  - pre-commit SAST

# Network
1. DAST (Dynamic Application Security Testing)
  - dynamic-scan-for-security-vulnerabilities
  - testing-for-bypassing-authentication-schema
2. DAST With Authenticated Sessions
  - DAST With Different Roles
3. Ensure Strong Authentication Everywhere
  - Testing for Weaker Authentication in Alternative Channel
3. API Fuzzing
  - api-fuzzing
  - Coverage of more input vectors
4. Coverage of Self Written Security Features
  - 4.4.7 Testing for Weak Password Policy
  - 4.5.3 Testing for Privilege Escalation
  - 4.5.4 Testing for Insecure Direct Object References
4. Application Resilience
  - load-tests
  - Do you perform denial of service and security stress testing?
5. Network Resilience
6. Infrastructure Resilience

# Design
1. NFR Requirements
  - creation-of-evil-user-stories
  - Refinement/Planning with Security Awareness
  - Care about BCDR / Definition of simple BCDR practices for critical components
1. Threat Modeling
  - conduction-of-threat-modeling
2. Security by Design Principles
  - get-to-know-your-design-flaws
  - follow-security-by-design-principles
    - application roles/secrets according to the least privilege principle
  - shared-security-services
2. DIST (Dynamic Infrastructure Security Testing)
  - Test network segmentation
  - test-security-configuration-of-cloud-environments
  - test-security-configuration-of-infrastructure
2. Infrastructure as Code
3. SIST (Static Infrastructure Security Testing)
  - test-security-configuration-of-cloud-environments
  - test-security-configuration-of-infrastructure
3. Threat Modeling from IaC

# Logging
- Profound Logging
  - logging-of-security-events
  - logging-concept
  - Visualized logging

# Ops
1. Application Metrics
  - Creation of Application Metrics
  - Visualization of Metrics
    - Screens with metric visualization
    - Dashboard
2. Alerting
  - Targeted Alerting on Metric Violations
3. Auto-Healing / Resilience
  - Advanced availability and stability metrics
  - Auto-Response on Metric Violation
2. Infrastructure Metrics
  - Creation of System Metrics
3. NFR Metrics
  - Metrics are combined with tests
    - Changes should not impact stability (metrics)
1. Defect Visualization
  - simple-visualization-of-defects
  - Advanced visualization of defects
2. Defect Metrics
  - Metrics on Test Results
  - Coverage and control metrics
- Security Control Metrics
  - Defense metrics

# Deployment
1. Artifact Integrity
  - same-artifact-for-environments
  - environment-dependent-configuration-parameters
1. Secrets Management
  - Key Store
  - Practice proper lifecycle management
1. Fail Safe Deployments
  - roll-back / roll-forward
  - backup-before-deployment

# 33
- Proper Software Development
  - Use proper programming languages #LangSec