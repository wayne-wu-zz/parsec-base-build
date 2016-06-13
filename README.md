# Parsec Base Build
The base build provides a parent build.gradle file for any Parsec project to inherit from. The build file includes
dependencies, build plugins, and necessary configurations that are used within a Parsec project. These external settings
are designed to enforce a standardized build process in which enhances the quality of the Parsec client's application.
It also includes the Parsec Gradle Plugin which is responsible for parsing the RDLs and generating files.

## Usage
The base build is essentially a Script Plugin and must be inherited using:
`apply from: 'https://raw.githubusercontent.com/wayne-wu/parsec-base-build/master/parsec.gradle'`

The parsec.gradle file includes all necessary dependencies for you to get started with a Parsec project.
