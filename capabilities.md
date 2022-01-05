# Initial
- Team Empowerment (self improvement
  - Risk Leadership  (make own decisions)
  - Onboard Management in Security
  - Continuously Improve
  - Review Activities
  - Empowerment path
    - Self-improvement use "Security-Chaos-Monkey" to get challenged
      - Incentive for teams who get better (metrics)
    - ctf on other teams systems
    - give feedback to everyone in the guilde to keep everyone honest

# Dependencies
1. Handling of Known Vulnerabilities on Request
  1. Test Server Side Libraries Regarding Known Vulnerabilities
  1. Test Client Side Libraries Regarding Known Vulnerabilities
  2. test-container-images-regarding-known-vulnerabilities
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
3. Prevent Bad Code on Commit
  - prevent-secrets-in-source-code
  - SAST

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
1. Threat Modeling
  - conduction-of-threat-modeling
2. Security by Design Principles
  - get-to-know-your-design-flaws
  - follow-security-by-design-principles
  - shared-security-services
2. DIST (Dynamic Infrastructure Security Testing)
  - Test network segmentation
2. Infrastructure as Code
3. SIST (Static Infrastructure Security Testing)
3. Threat Modeling from IaC
