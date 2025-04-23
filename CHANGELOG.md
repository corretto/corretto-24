# Change Log for Amazon Corretto 24

The following sections describe the changes for each release of Amazon Corretto 24.

## Corretto version: 24.0.1.9.1
Release Date: April 15, 2025
 
**Target Platforms**
 
+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 10 or later, x86_64
+ macos 13.0 and later, x86_64
+ macos 13.0 and later, aarch64
 
The following issues above are addressed in 24.0.1.9.1

| Issue Name | Platform | Description | Link |
|------------|----------|-------------|------|
| Import jdk-24.0.1+9 | All | Updates Corretto baseline to OpenJDK 24.0.1+9 | [jdk-24.0.1+9](https://github.com/openjdk/jdk24u/releases/tag/jdk-24.0.1+9) |
| (tz) Update Timezone Data to 2025b | All | Update tz code and data to use 2025b release | [JDK-8352716](https://bugs.openjdk.org/browse/JDK-8352716) |


The following CVEs are addressed in 24.0.1.9.1

| CVE | CVSS | Component |
|-----|------|-----------|
| CVE-2025-21587 | security-libs/javax.net.ssl | 7.4 |
| CVE-2025-30698 | client-libs/2d | 5.6 |
| CVE-2025-30691 | hotspot/compiler | 4.8 |

## Corretto version: 24.0.0.36.3
Release Date: March 19, 2025

**Target Platforms <sup>1</sup>**

+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64


**1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
in the Amazon Corretto FAQ for supported platforms

The following issues are addressed in 24.0.0.36.3:

| Issue Name                | Platform  | Description                                                                                                                                                               | Link                                                               |
|---------------------------|-----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| Remove java.policy and default.policy from build.gradle | All Linux | Following JEP486 [#1](https://github.com/corretto/corretto-24/pull/1) build.gradle was not updated to remove conf/security/java.policy and lib/security/default.policy. | [#7](https://github.com/corretto/corretto-24/pull/7)               |


## Corretto version: 24.0.0.36.2
Release Date: March 18, 2025

**Target Platforms <sup>1</sup>**

+ RPM-based Linux using glibc 2.17 or later, x86_64
+ Debian-based Linux using glibc 2.17 or later, x86_64
+ RPM-based Linux using glibc 2.17 or later, aarch64
+ Debian-based Linux using glibc 2.17 or later, aarch64
+ Alpine-based Linux, x86_64
+ Alpine-based Linux, aarch64
+ Windows 10 or later, x86_64
+ macos 13.0 and later, x86_64
+ macos 13.0 and later, aarch64


**1.** This is the platform targeted by the build. See [Using Amazon Corretto](https://aws.amazon.com/corretto/faqs/#Using_Amazon_Corretto)
in the Amazon Corretto FAQ for supported platforms

The following issues are addressed in 24.0.0.36.2:

| Issue Name                | Platform     | Description                                | Link                                                              |
|---------------------------|--------------|--------------------------------------------|-------------------------------------------------------------------|
| Import jdk-24+36          | All          | Updates Corretto baseline to OpenJDK 24+36 | [jdk-24+36](https://github.com/openjdk/jdk/releases/tag/jdk-24+36) |
| Generate man pages for AL | Amazon Linux | Include man pages in the config            | [Github PR](https://github.com/corretto/corretto-24/pull/5)       |