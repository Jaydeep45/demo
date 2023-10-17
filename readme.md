# Commands to update version
`mvn build-helper:parse-version versions:set@major`

This will increment the major version and set minor and patch version to 0.

`mvn build-helper:parse-version versions:set@minor`

This will increment the minor version and set patch version to zero.

`mvn build-helper:parse-version versions:set@patch`

This will increment the patch version. Afterwards you have to commit your changed back into your version control system

Links:
-   https://www.baeldung.com/maven-release-nexus
- https://thihenos.medium.com/maven-release-plugin-a-simple-example-of-package-management-9926506acfb9
- https://www.javafixing.com/2022/03/fixed-how-to-apply-semantic-versioning.html?m=1