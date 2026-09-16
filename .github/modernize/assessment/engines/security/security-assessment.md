# Security Assessment Report

**Generated:** 2026-09-16T02:38:47.0000000Z

## Summary

| Metric | Count |
|--------|-------|
| Total Findings | 46 |
| CVE Vulnerabilities | 45 |
| CWE Vulnerabilities | 1 |
| Total Rules Assessed | 59 |
| Rules Passed | 58 |

### By Severity

| Severity | Count |
|----------|-------|
| mandatory | 45 |
| optional | 1 |
| potential | 0 |


## CVE Findings (Dependency Vulnerabilities)

### CVE-2026-65905: Apache Tomcat's DIGEST authenticator has an Authentication Bypass by Capture-replay vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-65905](https://github.com/advisories/GHSA-9xv2-5v5q-p794): Apache Tomcat's DIGEST authenticator has an Authentication Bypass by Capture-replay vulnerability

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.25 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.58 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.121 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))

### CVE-2026-65182: Apache Tomcat has an Improper Access Control, Incorrect Authorization vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-65182](https://github.com/advisories/GHSA-gcx9-497g-6cp6): Apache Tomcat has an Improper Access Control, Incorrect Authorization vulnerability

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.25 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.58 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.121 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))

### CVE-2026-68525: Apache Tomcat's FORM authentication process has an Incorrect Authorization vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-68525](https://github.com/advisories/GHSA-h3x4-894j-xpx5): Apache Tomcat's FORM authentication process has an Incorrect Authorization vulnerability

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.25 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.58 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.121 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))

### GHSA-r7wm-3cxj-wff9: jackson-core: Async parser maxNumberLength bypass via chunked digit accumulation (incomplete fix for GHSA-72hv-8253-57qq)
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[GHSA-r7wm-3cxj-wff9](https://github.com/advisories/GHSA-r7wm-3cxj-wff9): jackson-core: Async parser maxNumberLength bypass via chunked digit accumulation (incomplete fix for GHSA-72hv-8253-57qq)

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-core:2.13.5 (pom.xml (transitive dependency)); upgrade to 2.18.8 or later
  - com.fasterxml.jackson.core:jackson-core:2.13.5 (pom.xml (transitive dependency)); upgrade to 2.21.4 or later

### CVE-2026-54513: jackson-databind has an array subtype allowlist bypass in BasicPolymorphicTypeValidator (allowIfSubTypeIsArray)
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-54513](https://github.com/advisories/GHSA-rmj7-2vxq-3g9f): jackson-databind has an array subtype allowlist bypass in BasicPolymorphicTypeValidator (allowIfSubTypeIsArray)

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.13.5 (pom.xml (transitive dependency)); upgrade to 2.18.8 or later
  - com.fasterxml.jackson.core:jackson-databind:2.13.5 (pom.xml (transitive dependency)); upgrade to 2.21.4 or later
  - com.fasterxml.jackson.core:jackson-databind:2.13.5 (pom.xml (transitive dependency)); upgrade to 3.1.4 or later

### CVE-2026-54512: jackson-databind has a PolymorphicTypeValidator bypass via generic type parameters that allows arbitrary class instantiation
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-54512](https://github.com/advisories/GHSA-j3rv-43j4-c7qm): jackson-databind has a PolymorphicTypeValidator bypass via generic type parameters that allows arbitrary class instantiation

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-databind:2.13.5 (pom.xml (transitive dependency)); upgrade to 2.18.8 or later
  - com.fasterxml.jackson.core:jackson-databind:2.13.5 (pom.xml (transitive dependency)); upgrade to 3.1.4 or later
  - com.fasterxml.jackson.core:jackson-databind:2.13.5 (pom.xml (transitive dependency)); upgrade to 2.21.4 or later

### CVE-2026-41850: Spring Framework Algorithmic Denial of Service via SpEL Expressions
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-41850](https://github.com/advisories/GHSA-r5w3-xv2f-j59q): Spring Framework Algorithmic Denial of Service via SpEL Expressions

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-expression:5.3.31 (pom.xml (transitive dependency)); upgrade to 7.0.8 or later
  - org.springframework:spring-expression:5.3.31 (pom.xml (transitive dependency)); upgrade to 6.2.19 or later
  - org.springframework:spring-expression:5.3.31 (pom.xml (transitive dependency))
  - org.springframework:spring-expression:5.3.31 (pom.xml (transitive dependency))

### CVE-2026-41849: Spring Framework Denial of Service via Integer Overflow in SpEL Expressions
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-41849](https://github.com/advisories/GHSA-775g-4xr8-78h8): Spring Framework Denial of Service via Integer Overflow in SpEL Expressions

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-expression:5.3.31 (pom.xml (transitive dependency))

### CVE-2026-41845: Spring Framework Cross-site Scripting via JavaScriptUtils
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-41845](https://github.com/advisories/GHSA-3chg-m5w7-qfv5): Spring Framework Cross-site Scripting via JavaScriptUtils

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency)); upgrade to 7.0.8 or later
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency)); upgrade to 6.2.19 or later
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency))
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency))

### CVE-2026-41842: Spring Framework Denial of Service via Versioned Resources in Spring MVC and WebFlux
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-41842](https://github.com/advisories/GHSA-x23c-287f-qqv5): Spring Framework Denial of Service via Versioned Resources in Spring MVC and WebFlux

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency)); upgrade to 7.0.8 or later
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency)); upgrade to 6.2.19 or later
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency))
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency))

### CVE-2026-41284: Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-41284](https://github.com/advisories/GHSA-gx5v-xp9w-j4cg): Apache Tomcat: Unbounded read in WebDAV LOCK and  PROPFIND handling

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.118 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.55 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.22 or later

### CVE-2026-43512: Apache Tomcat - Digest authenticator will authenticate any unknown user
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-43512](https://github.com/advisories/GHSA-h6fc-48rj-7qqh): Apache Tomcat - Digest authenticator will authenticate any unknown user

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.118 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.55 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.22 or later

### CVE-2026-43513: Apache Tomcat: LockOutRealm treats user names as case-sensitive
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-43513](https://github.com/advisories/GHSA-5mp6-jrq3-r938): Apache Tomcat: LockOutRealm treats user names as case-sensitive

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.118 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.55 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.22 or later

### CVE-2026-43515: Apache Tomcat - Security constraints not correctly applied
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-43515](https://github.com/advisories/GHSA-5m62-pw8w-7w9f): Apache Tomcat - Security constraints not correctly applied

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.118 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.55 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.22 or later

### CVE-2026-41293: Apache Tomcat - HTTP/2 request headers not validated
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-41293](https://github.com/advisories/GHSA-r29c-68gh-xp6x): Apache Tomcat - HTTP/2 request headers not validated

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.55 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.22 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.118 or later

### CVE-2026-42498: Apache Tomcat - WebSocket authentication header exposure
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-42498](https://github.com/advisories/GHSA-fv25-8xcx-gqjc): Apache Tomcat - WebSocket authentication header exposure

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.118 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.55 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.22 or later

### CVE-2026-40973: Spring Boot accepts predictable temp directory without ownership verification
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-40973](https://github.com/advisories/GHSA-wwpq-f5c3-7hvx): Spring Boot accepts predictable temp directory without ownership verification

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot:2.7.18 (pom.xml (transitive dependency)); upgrade to 4.0.6 or later
  - org.springframework.boot:spring-boot:2.7.18 (pom.xml (transitive dependency)); upgrade to 3.5.14 or later
  - org.springframework.boot:spring-boot:2.7.18 (pom.xml (transitive dependency))
  - org.springframework.boot:spring-boot:2.7.18 (pom.xml (transitive dependency))
  - org.springframework.boot:spring-boot:2.7.18 (pom.xml (transitive dependency))

### CVE-2026-34483: Apache Tomcat has an Improper Encoding or Escaping of Output vulnerability in the JsonAccessLogValve
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-34483](https://github.com/advisories/GHSA-rv64-5gf8-9qq8): Apache Tomcat has an Improper Encoding or Escaping of Output vulnerability in the JsonAccessLogValve

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.116 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.54 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.21 or later

### CVE-2026-34487: Apache Tomcat vulnerable to Insertion of Sensitive Information into Log File
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-34487](https://github.com/advisories/GHSA-x4m4-345f-5h5g): Apache Tomcat vulnerable to Insertion of Sensitive Information into Log File

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.117 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.54 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.21 or later

### CVE-2026-24880: Apache Tomcat has an HTTP Request/Response Smuggling vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-24880](https://github.com/advisories/GHSA-563x-q5rq-57qp): Apache Tomcat has an HTTP Request/Response Smuggling vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.116 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.52 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.20 or later

### CVE-2026-24734: Apache Tomcat has an Improper Input Validation vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-24734](https://github.com/advisories/GHSA-mgp5-rv84-w37q): Apache Tomcat has an Improper Input Validation vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.18 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.52 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.115 or later

### CVE-2025-55752: Apache Tomcat Vulnerable to Relative Path Traversal
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-55752](https://github.com/advisories/GHSA-wmwf-9ccg-fff5): Apache Tomcat Vulnerable to Relative Path Traversal

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.11 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.45 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.109 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))

### CVE-2025-48989: Apache Tomcat Improper Resource Shutdown or Release vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-48989](https://github.com/advisories/GHSA-gqp3-2cvr-x8m3): Apache Tomcat Improper Resource Shutdown or Release vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.10 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.44 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.108 or later

### CVE-2025-53506: Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-53506](https://github.com/advisories/GHSA-25xr-qj8w-c4vf): Apache Tomcat Coyote vulnerable to Denial of Service via excessive HTTP/2 streams

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.107 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.43 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.9 or later

### CVE-2025-52520: Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-52520](https://github.com/advisories/GHSA-wr62-c79q-cv37): Apache Tomcat Catalina is vulnerable to DoS attack through bypassing of size limits

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.9 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.43 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.107 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))

### CVE-2025-52999: jackson-core can throw a StackoverflowError when processing deeply nested data
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-52999](https://github.com/advisories/GHSA-h46c-h94j-95f3): jackson-core can throw a StackoverflowError when processing deeply nested data

Severity: HIGH

Affected dependencies:
  - com.fasterxml.jackson.core:jackson-core:2.13.5 (pom.xml (transitive dependency)); upgrade to 2.15.0 or later

### CVE-2025-48988: Apache Tomcat - DoS in multipart upload
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-48988](https://github.com/advisories/GHSA-h3gc-qfqq-6h8f): Apache Tomcat - DoS in multipart upload

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.8 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.42 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.106 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))

### CVE-2025-22235: Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-22235](https://github.com/advisories/GHSA-rc42-6c7j-7h5r): Spring Boot EndpointRequest.to() creates wrong matcher if actuator endpoint is not exposed

Severity: HIGH

Affected dependencies:
  - org.springframework.boot:spring-boot:2.7.18 (pom.xml (transitive dependency))
  - org.springframework.boot:spring-boot:2.7.18 (pom.xml (transitive dependency))
  - org.springframework.boot:spring-boot:2.7.18 (pom.xml (transitive dependency))
  - org.springframework.boot:spring-boot:2.7.18 (pom.xml (transitive dependency)); upgrade to 3.3.11 or later
  - org.springframework.boot:spring-boot:2.7.18 (pom.xml (transitive dependency)); upgrade to 3.4.5 or later

### CVE-2025-24813: Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-24813](https://github.com/advisories/GHSA-83qj-6fr2-vhqg): Apache Tomcat: Potential RCE and/or information disclosure and/or information corruption with partial PUT

Severity: CRITICAL

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.3 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.35 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.99 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))

### CVE-2024-56337: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-56337](https://github.com/advisories/GHSA-27hp-xhwr-wr2m): Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.2 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.34 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.98 or later

### CVE-2024-38819: Spring Framework Path Traversal vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-38819](https://github.com/advisories/GHSA-g5vr-rgqm-vf78): Spring Framework Path Traversal vulnerability

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency)); upgrade to 6.1.14 or later
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency))
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency))

### CVE-2024-50379: Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-50379](https://github.com/advisories/GHSA-5j33-cvvr-w245): Apache Tomcat Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.2 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.34 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.98 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))

### CVE-2024-38286: Apache Tomcat Allocation of Resources Without Limits or Throttling vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-38286](https://github.com/advisories/GHSA-7jqf-v358-p8g7): Apache Tomcat Allocation of Resources Without Limits or Throttling vulnerability

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.0-M21 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.25 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.90 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))

### CVE-2024-38816: Path traversal vulnerability in functional web frameworks
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-38816](https://github.com/advisories/GHSA-cx7f-g6mp-7hqm): Path traversal vulnerability in functional web frameworks

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency)); upgrade to 6.1.13 or later
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency))
  - org.springframework:spring-webmvc:5.3.31 (pom.xml (transitive dependency))

### CVE-2024-34750: Apache Tomcat - Denial of Service
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-34750](https://github.com/advisories/GHSA-wm9w-rjj3-j356): Apache Tomcat - Denial of Service

Severity: HIGH

Affected dependencies:
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 11.0.0-M21 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 10.1.25 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency)); upgrade to 9.0.90 or later
  - org.apache.tomcat.embed:tomcat-embed-core:9.0.83 (pom.xml (transitive dependency))

### CVE-2024-22262: Spring Framework URL Parsing with Host Validation
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-22262](https://github.com/advisories/GHSA-2wrp-6fg6-hmc5): Spring Framework URL Parsing with Host Validation

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web:5.3.31 (pom.xml (transitive dependency)); upgrade to 5.3.34 or later
  - org.springframework:spring-web:5.3.31 (pom.xml (transitive dependency)); upgrade to 6.0.19 or later
  - org.springframework:spring-web:5.3.31 (pom.xml (transitive dependency)); upgrade to 6.1.6 or later

### CVE-2024-22259: Spring Framework URL Parsing with Host Validation Vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-22259](https://github.com/advisories/GHSA-hgjh-9rj2-g67j): Spring Framework URL Parsing with Host Validation Vulnerability

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web:5.3.31 (pom.xml (transitive dependency)); upgrade to 6.1.5 or later
  - org.springframework:spring-web:5.3.31 (pom.xml (transitive dependency)); upgrade to 6.0.18 or later
  - org.springframework:spring-web:5.3.31 (pom.xml (transitive dependency)); upgrade to 5.3.33 or later

### CVE-2024-22243: Spring Web vulnerable to Open Redirect or Server Side Request Forgery
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2024-22243](https://github.com/advisories/GHSA-ccgv-vj62-xf9h): Spring Web vulnerable to Open Redirect or Server Side Request Forgery

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-web:5.3.31 (pom.xml (transitive dependency)); upgrade to 6.1.4 or later
  - org.springframework:spring-web:5.3.31 (pom.xml (transitive dependency)); upgrade to 6.0.17 or later
  - org.springframework:spring-web:5.3.31 (pom.xml (transitive dependency)); upgrade to 5.3.32 or later
  - org.springframework:spring-web:5.3.31 (pom.xml (transitive dependency))

### CVE-2023-6481: Logback is vulnerable to an attacker mounting a Denial-Of-Service attack by sending poisoned data
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-6481](https://github.com/advisories/GHSA-gm62-rw4g-vrc4): Logback is vulnerable to an attacker mounting a Denial-Of-Service attack by sending poisoned data

Severity: HIGH

Affected dependencies:
  - ch.qos.logback:logback-core:1.2.12 (pom.xml (transitive dependency)); upgrade to 1.4.14 or later
  - ch.qos.logback:logback-core:1.2.12 (pom.xml (transitive dependency)); upgrade to 1.3.14 or later
  - ch.qos.logback:logback-core:1.2.12 (pom.xml (transitive dependency)); upgrade to 1.2.13 or later

### CVE-2023-6378: logback serialization vulnerability
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2023-6378](https://github.com/advisories/GHSA-vmq6-5m68-f53m): logback serialization vulnerability

Severity: HIGH

Affected dependencies:
  - ch.qos.logback:logback-classic:1.2.12 (pom.xml (transitive dependency)); upgrade to 1.4.12 or later
  - ch.qos.logback:logback-core:1.2.12 (pom.xml (transitive dependency)); upgrade to 1.4.12 or later
  - ch.qos.logback:logback-classic:1.2.12 (pom.xml (transitive dependency)); upgrade to 1.3.12 or later
  - ch.qos.logback:logback-core:1.2.12 (pom.xml (transitive dependency)); upgrade to 1.3.12 or later
  - ch.qos.logback:logback-core:1.2.12 (pom.xml (transitive dependency)); upgrade to 1.2.13 or later
  - ch.qos.logback:logback-classic:1.2.12 (pom.xml (transitive dependency)); upgrade to 1.2.13 or later

### CVE-2022-1471: SnakeYaml Constructor Deserialization Remote Code Execution
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-1471](https://github.com/advisories/GHSA-mjmj-j48q-9wg2): SnakeYaml Constructor Deserialization Remote Code Execution

Severity: HIGH

Affected dependencies:
  - org.yaml:snakeyaml:1.30 (pom.xml (transitive dependency)); upgrade to 2.0 or later

### CVE-2022-25857: Uncontrolled Resource Consumption in snakeyaml
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2022-25857](https://github.com/advisories/GHSA-3mc7-4q67-w48m): Uncontrolled Resource Consumption in snakeyaml

Severity: HIGH

Affected dependencies:
  - org.yaml:snakeyaml:1.30 (pom.xml (transitive dependency)); upgrade to 1.31 or later

### CVE-2016-1000027: Pivotal Spring Framework contains unsafe Java deserialization methods
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2016-1000027](https://github.com/advisories/GHSA-4wrc-f8pq-fpqp): Pivotal Spring Framework contains unsafe Java deserialization methods

Severity: CRITICAL

Affected dependencies:
  - org.springframework:spring-web:5.3.31 (pom.xml (transitive dependency)); upgrade to 6.0.0 or later

### CVE-2026-24400: AssertJ has XML External Entity (XXE) vulnerability when parsing untrusted XML via isXmlEqualTo assertion
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2026-24400](https://github.com/advisories/GHSA-rqfh-9r24-8c9r): AssertJ has XML External Entity (XXE) vulnerability when parsing untrusted XML via isXmlEqualTo assertion

Severity: HIGH

Affected dependencies:
  - org.assertj:assertj-core:3.22.0 (pom.xml (transitive dependency)); upgrade to 3.27.7 or later

### CVE-2025-41249: Spring Framework annotation detection mechanism may result in improper authorization
- **Severity:** mandatory
- **Story Points:** 1
- **Files:** pom.xml

[CVE-2025-41249](https://github.com/advisories/GHSA-jmp9-x22r-554x): Spring Framework annotation detection mechanism may result in improper authorization

Severity: HIGH

Affected dependencies:
  - org.springframework:spring-core:5.3.31 (pom.xml (transitive dependency))
  - org.springframework:spring-core:5.3.31 (pom.xml (transitive dependency))
  - org.springframework:spring-core:5.3.31 (pom.xml (transitive dependency)); upgrade to 6.2.11 or later


## CWE Findings (Code-Level Vulnerabilities)

### CWE-79: Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')
- **Category:** Injection Attacks
- **Severity:** optional
- **Story Points:** 8
- **Files:** src/main/webapp/WEB-INF/jsp/orders/new.jsp:63, src/main/java/com/acme/scm/frontend/controller/OrderController.java:59

OrderController.createOrder binds user-controlled PurchaseOrderDTO fields and returns the orders/new JSP after an error. The JSP interpolates order.orderNumber at line 63 and other fields using unescaped JSP EL, allowing a supplied HTML/JavaScript payload to be rendered.
