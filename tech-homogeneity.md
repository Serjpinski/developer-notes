# Pros and cons of technology and tool homogeneity/heterogeneity in a medium sized IT team

Advantages of homogeneity:
* Reduces maintenance and operational costs. By using similar tools and libraries in all projects, any developer can quickly contribute or fix any project, and all projects can share the same operation/deployment infrastructure.
* Reduces bug rate, since code interacting with tools can be very similar on all projects.

Disadvantages of homogeneity:
* Upgrading or migrating a tool for all projects in the platform can be hard, dangerous or costly, so a very rigid homogeneity can lead to tech stagnation.
* New bugs in code interacting with a tool can affect all projects using the tool (this is why previous point can be dangerous).
* New bugs inside a tool can affect all projects using the tool.

Advantages of heterogeneity:
* Allows the team developing a project to choose the tools more suited for that specific project.
* Allows to try state-of-the-art tools that may have a positive influence in the future of the platform.

Disadvantages of heterogeneity:
* Only the team that developed a project knows how to maintain it. Other developers must learn the tools before contributing to the project.
