# dummy-connector

An OpenICF connector built to work with the [ForgeRock Identity Management Provisioning System](https://www.forgerock.co
m/platform/identity-management/identity-provisioning). This connector maintains an in-memory hash map and performs mock 
CRUD operations - perfect for testing!

**NOTE:** This is a community connector and is made available so that customers with a ForgeRock subscription can build,
 develop or fork this repository. See the legal disclaimer bit below.

## Building
The code in this repository has binary dependencies that live in the ForgeRock maven repository. Maven can be configured
 to authenticate to this repository by following the following [ForgeRock Knowledge Base Article]
 (https://backstage.forgerock.com/knowledge/kb/article/a74096897).

To get and build this repository you will need a build environment that has git, maven and a JDK installed. 

This has been confirmed as buildin with Maven 3.3.3, Oracle JDK 1.8.0_91. 

```
$ git clone <repo_url>
$ cd <repo_url>
$ mvn clean install
```

## Licensing

The Code and binaries are covered under the [CDDL 1.0 license](https://forgerock.org/cddlv1-0/). Essentially you may use
 the release binaries in production at your own risk.

### Legal Disclaimer Bit
All components herein are provided AS IS and without a warranty of any kind by ForgeRock or any licensors of such code. 
ForgeRock and all licensors of such code disclaims all liability or obligations of such code and any use, distribution 
or operation of such code shall be exclusively subject to the licenses contained in each file and recipient is obligated
 to read and understand each such license before using the Software. Notwithstanding anything to the contrary, ForgeRock
  has no obligations for the use or support of such code under any ForgeRock license agreement.
