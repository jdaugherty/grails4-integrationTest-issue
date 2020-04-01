# grails4-integrationTest-issue
Project that when gradle refresh is run in intellij, resets test source marking

# Idea plugin generates correct sources
With intellij closed, run `gradle cleanIdea idea` and then reopen the project.  The project will have the test sources marked correctly.

# Gradle import causes test source markings to be lost
The first time gradle import/refresh is run in IntelliJ, it will mark the integration-test sources as production instead of test.
