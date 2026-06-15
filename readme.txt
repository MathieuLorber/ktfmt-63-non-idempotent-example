curl -L https://github.com/facebook/ktfmt/releases/download/v0.63/ktfmt-0.63-with-dependencies.jar -o ktfmt.jar
# tested on openjdk 25 2025-09-16 LTS
java -jar ktfmt.jar --kotlinlang-style KtfmtProblem.kt
