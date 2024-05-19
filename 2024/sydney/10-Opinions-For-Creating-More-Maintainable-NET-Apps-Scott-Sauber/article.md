# 10 Opinions For Creating More Maintainable .NET Apps - Scott Sauber - NDC Sydney 2024

- **Folder Structure**: Instead of creating separate folders for Controllers and Models, it is more practical to organize the project by feature. This means placing all files related to a specific feature within a single folder, enhancing modularity and maintainability.

![Folder Structure Image](/2024/sydney/10-Opinions-for-Creating-More-Maintainable-NET-Apps-Scott-Sauber/images/Folder-Structure-Image.png)

- **Horizontal Slicing**: Only slice horizontally when publishing packages to NuGet or for internal distribution.

- **Treat Warnings as Errors**: Ensure that all warnings are treated as errors to maintain high code quality.

- **Logging Metrics**: When logging, it is important to track two types of metrics:
  - *Application Metrics*: Such as response time, CPU usage, etc.
  - *Business Metrics*: Such as the number of times a button was clicked, user interactions, etc.

- **Fallback Policy**: Define a default fallback policy to handle cases where no specific policy is defined.

![Fallback Policy Image](/2024/sydney/10-Opinions-for-Creating-More-Maintainable-NET-Apps-Scott-Sauber/images/Fallback-Policy-Image.png)

- **Remove Service Headers**: By default, ASP.NET adds certain headers that reveal internal workings. It's best practice to remove these headers to avoid exposing details about the backend.

![Remove Headers Image](/2024/sydney/10-Opinions-for-Creating-More-Maintainable-NET-Apps-Scott-Sauber/images/Remove-Headers-Image.png)

- **Centralized IOptions Registration**: Instead of injecting IOptions everywhere, it’s more efficient to register it in a single location.

![IOptions Image](/2024/sydney/10-Opinions-for-Creating-More-Maintainable-NET-Apps-Scott-Sauber/images/IOptions-Image.png)

- **Version Endpoint**: Defining an API version endpoint is beneficial. For example, a request to `/api/version` should return the version in a structured format.

![Version Format Image](/2024/sydney/10-Opinions-for-Creating-More-Maintainable-NET-Apps-Scott-Sauber/images/Version-Format-Image.png)

- **Happy Path at the End**: Place the successful path (happy path) at the end of the method. Perform checks and handle errors at the beginning, returning early if necessary, and only proceed to the successful outcome at the method's end.

![Happy Path Image](/2024/sydney/10-Opinions-for-Creating-More-Maintainable-NET-Apps-Scott-Sauber/images/Happy-Path-Image.png)

- **HTTP Security Headers**: Adding security headers is crucial for HTTP security. There are open-source libraries available to help with this.

![HTTP Security Headers Image](/2024/sydney/10-Opinions-for-Creating-More-Maintainable-NET-Apps-Scott-Sauber/images/HTTP-Security-Headers-Image.png)


- **ValidateOnBuild**: It’s important to use ValidateOnBuild to ensure configurations are validated at build time.

![ValidateOnBuild Image](/2024/sydney/10-Opinions-for-Creating-More-Maintainable-NET-Apps-Scott-Sauber/images/ValidateOnBuild-Image.png)

- **FluentAssertions**: Use the FluentAssertions library for more expressive and meaningful assertions in tests.
 
![Fluent Assertions Image](/2024/sydney/10-Opinions-for-Creating-More-Maintainable-NET-Apps-Scott-Sauber/images/Fluent-Assertions-Image.png)

- **Central Package Management in .NET 6+**: With the Central Package Management feature introduced in .NET 6, you can define commonly referenced packages in a Directory.Packages.props file. To use this, remove the Version attribute from PackageReference.

![Central Package Management Image](/2024/sydney/10-Opinions-for-Creating-More-Maintainable-NET-Apps-Scott-Sauber/images/Central-Package-Management-Image.png)



