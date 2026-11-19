# sca-vuln-java-maven

> **WARNING: Intentionally vulnerable.** Test fixture for Software Composition Analysis (SCA) tools.
> Do not deploy. Dependencies are pinned to versions with known CVEs.

**Ecosystem:** Maven (Java)

## Expected findings (non-exhaustive)
- log4j-core 2.14.1: CVE-2021-44228 (Log4Shell), CVE-2021-45046
- jackson-databind 2.9.8: many deserialization CVEs
- spring-webmvc/spring-beans 5.3.17: CVE-2022-22965 (Spring4Shell)
- commons-collections 3.2.1: CVE-2015-7501
- commons-text 1.9: CVE-2022-42889 (Text4Shell)
- h2 1.4.199: CVE-2021-42392, CVE-2022-23221
- snakeyaml 1.26: CVE-2022-1471
