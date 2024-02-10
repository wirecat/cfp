# Title
Should I use Inversion of Control Containers in Go?

# Abstract
Inversion of Control (IoC) Containers, evil or just misunderstood? Lets explore this tool at a high level so you can decide for yourself. We'll cover what an IoC Container is, when to use it, when not to use it, and some things to watch out for.

# Format
I chose the 25-Minute track vs. the more in-depth 45 minute track because I believe the community would benefit more from a high-level overview of IoC Containers vs. a deep dive.

25-Minute Talk - Should present big ideas of general interest to the entire attendee base. The audience will be comprised of Go programmers of all experience levels.

# Outline
* (5 Minutes) Introduction
    * Who am I and what's my background
    * My experiences with the Go community's polarized views on IoC Containers
* (5 Minutes) What is an Inversion of Control Container?
    * Decouples dependency creation and consumption
    * Main approaches to IoC Containers (runtime vs compile time)
* (5 Minutes) Why use an IoC Container?
    * Adding a dependency doesn't require modifying the entire dependency tree
    * Extending the system can be as simple as implementing an interface and registering it with the container
* (5 Minutes) When Not to Use an IoC Container
    * Simple applications with simple dependency trees
    * Applications with a strict performance requirement
* (5 Minutes) Things to Watch For
    * Binding failures at runtime
    * Can make code harder to understand/follow code paths
    * Service Locator Pattern - Please don't!
* (2 Minutes) Conclusion
    * Recap of the main points
    * Final thoughts
    * Present slide with list of resources (IoC Container projects in Go, my contact information, etc.)
    * Give thanks

# Speaker Biography
Daniel is a developer at GitHub who is fortunate to work with a talented and compassionate team focused on making a positive developer experience for everyone. Daniel loves collobaration and the shared experience of growth through learning and teaching.
