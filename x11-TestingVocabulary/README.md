# Exercise 11: Software Testing Vocabulary

We have discussed and practiced unit testing, test-driven development (TDD), and testing metrics in depth. However, there are other important and related topics in testing.

As a team, you will study one other area in software testing to teach the rest of class. Visit the [wiki for Software Testing Vocabulary](https://github.com/ChicoState/SoftwareEngineering/wiki/Software-Testing-Vocabulary) and see which area your team has been assigned. Your team needs to edit the wiki page to include a summary of **what** the term is, **why** we care about it, **examples** of how it applies in a real-life situation, and **sources** you used as references (and helpful links for more information). Along with the edited wiki page, you should prepare to teach a mini 10-minute lesson on it as a team.

## Schedule

**Wednesday**

* Akka: Edge & Corners cases and Boundary Testing

* Apache Spark: Sanity and Regression Testing

* MouseTrap: Integration and System Testing

* Mozilla: Alpha and Beta Testing

**Friday**

* RethinkDB: Acceptance Testing

* BossyUI: White Box and Black Box Testing

* KDevelop: Mutation Testing

## Review and Discussion

1. In the ConnectX example, a function had a bug only in the situation where *both* the width was invalid *and* the height was valid. What is the name for this sort of situation? Why?

2. Draw a diagram that represents the relationship between *unit*, *integration*, and *system* testing.

3. Using the software testing vocabulary learned in this lesson, describe the benefits specific to **automating** unit tests.

4. Mutation Testing may change boolean comparison operators (e.g. less-than, equal-to, etc) to create mutants. What type of testing strategy should developers take to make sure their tests "kill" those mutants?

5. In the software development process, when do you think *acceptance testing* should be conducted with respect to Alpha and Beta testing? Why?

6. Review each type of testing listed in this vocabulary list; for each one, describe whether you think it should (or must!) be performed as *White box* or *Black box* testing. Explain why.
