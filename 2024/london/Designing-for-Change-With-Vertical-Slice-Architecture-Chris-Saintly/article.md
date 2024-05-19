# Designing for change with Vertical Slice Architecture, Chris Saintly, NDC London 2024

When starting a project, several key decisions need to be made, including:

- **Technology**: The core technology stack that will be used.
- **Frameworks and Libraries**: The specific tools and libraries to facilitate development.
- **Patterns and Practices**: The architectural and coding standards to ensure consistency and maintainability.
- **Requirements**: The project requirements, which often change frequently and can be unpredictable.

In the late 1990s, the N-Tier architecture was widely used. 

![N-Tier Image](/2024/london/Designing-for-change-with-Vertical-Slice-Architecture-Chris-Saintly/images/N-Tier-Image.png)


However, in the early 2000s, the Onion Architecture started gaining popularity. This architecture is closely related to Domain-Driven Design (DDD) and emphasizes the separation of concerns.

![Onion Image](/2024/london/Designing-for-change-with-Vertical-Slice-Architecture-Chris-Saintly/images/Onion-Image.png)


By the 2010s, Clean Architecture emerged.

![Onion Image](/2024/london/Designing-for-change-with-Vertical-Slice-Architecture-Chris-Saintly/images/Clean-Image.png)


Despite the advantages of these architectures, developers often encountered issues like high coupling and low cohesion. Over time, maintaining and scaling the codebases built with these patterns became more complex and challenging to manage.


In response to these challenges, the concept of developing software not by layers but by features was introduced. This led to the Vertical Slice Pattern, proposed by the engineer behind popular libraries such as Automapper and MediatR.

![Future Image](/2024/london/Designing-for-change-with-Vertical-Slice-Architecture-Chris-Saintly/images/Future-Image.png)

The Vertical Slice Pattern addresses high coupling and low cohesion by organizing code around features rather than technical layers. This approach simplifies versioning features and makes it easier to maintain and scale the codebase.

![Future Versioning Image](/2024/london/Designing-for-change-with-Vertical-Slice-Architecture-Chris-Saintly/images/Future-Versioning-Image.png)

Moreover, the Vertical Slice Pattern allows for better modularity and a clearer separation of responsibilities, enhancing both development and maintenance efficiency. By aligning code organization with business functionality, developers can achieve greater flexibility and adaptability in their projects.