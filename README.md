# KotlinExtensionUtils
A Kotlin extension library for all Android developers for boilerplate code

Contribute your kotlin extension code in this **ExtensionUtils** file.

Step 1. Add it in your root build.gradle at the end of repositories:

        allprojects {
            repositories {
              ...
              maven {
                    name = "KotlinExtensionUtils"
                    url = uri("https://maven.pkg.github.com/shmehdi01/KotlinExtensionUtils")
               }
            }
          }

Step 2. Add the dependency

         dependencies {
                implementation 'shmehdi.libraires:extensionutils:1.0.0'
          }
