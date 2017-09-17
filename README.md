# FRC-2017-Steamworks-Gradle
We are attempting to get last year's code working in Gradle, this should let us use Intellij IDEA.

This is the plugin we are using for it:
https://github.com/Open-RIO/GradleRIO


## How to run this from the CLI

```Bash
# Clone Repo
git clone git@github.com:Team1091/FRC-2017-Steamworks-Gradle.git
cd FRC-2017-Steamworks-Gradle

# To build
./gradlew build

# To build and deploy
./gradlew build deploy

# To build and deploy without internet access (which is probably more common)
./gradlew build deploy --offline 
```
