# I picked java language for answereing these quetion.


## Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by google.

Some of the tools which can be used with java for linting are Checkstyle,Lightrun,PMD,Uncrustify,Error-Prone,Tattletale,UCDetector,Linter for Scala,Scalastyle,Coala. Out of these most popular once are checkstyle,lintrun and PMD. Checkstyle and Lintrun are specific for java but PMD supports multiple other programming language.

Some testing tools for java

JUnit.
Mockito.
Selenium.
TestNG.
Spock Framework.
Cucumber.
FitNesse.
Arquillian.

Some building tools for java

Apache Maven
Ant with ivy
Gradle
SBT

### What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask google!

CircleCI, TeamCity, Bamboo and Gilab are some tools for setting up CI.


### Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

For self hosted env one has to take care of hardware and software maintainence. But this can reduce the cost drastically as compared to cloud or Saas based alternative.

The challenges with saas based Ci is that it might not have feature or it might not be able to pivot if requirment of the user changes. Self hosted Ci can be customized as per the requirement.

So both the option has there own advantage and disadvantage. One has to consider above points in deciding what kind of setup would be a good fit for their project.



