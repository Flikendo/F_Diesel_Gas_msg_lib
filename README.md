# F_Diesel_Gas_msg_lib

This is a protobuf project which contains thoses clases to connect app to database.


## Protobuf Plugin for Gradle
This info is taken from [Protobuf Plugin for Gradle](https://github.com/google/protobuf-gradle-plugin)

The Gradle plugin that compiles Protocol Buffer (aka. Protobuf) definition files (*.proto) in your project. There are two pieces of its job:

1. It assembles the Protobuf Compiler (protoc) command line and uses it to generate Java source files out of your proto files.
2. It adds the generated Java source files to the input of the corresponding Java compilation unit (sourceSet in a Java project; variant in an Android project), so that they can be compiled along with your Java sources.
Note if you are generating non-Java/Kotlin source files, they will not be included for compilation automatically, you will need to add them to sources for language-specific compilations. See details in Default options section.
For more information about the Protobuf Compiler, please refer to [Google Developers Site](https://developers.google.com/protocol-buffers/docs/reference/java-generated?csw=1).
