curl -L https://github.com/facebook/ktfmt/releases/download/v0.64/ktfmt-0.64-with-dependencies.jar -o ktfmt.jar
# tested on openjdk 25 2025-09-16 LTS
java -jar ktfmt.jar --kotlinlang-style KtfmtProblem.kt
