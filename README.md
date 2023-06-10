# Code Generator for Java Spring Boot

This is a Java Spring Boot code generator that helps generate boilerplate code for your application. It provides a streamlined way to generate common components such as entities, controllers, services, and data access layers based on your database schema.

## Features

- Console-based input: Allows you to interactively specify the table names for which you want to generate code.
- Global configuration: Provides a global configuration for the code generation process, including output directory, author name, file override settings, and Swagger annotations for entity properties.
- Data source configuration: Allows you to configure the database connection details, such as URL, driver name, username, and password.
- Package configuration: Lets you specify the package structure for the generated code, including controller, entity, service, service implementation, and mapper classes.
- Custom configuration: Provides the option to customize the code generation process through the `InjectionConfig`, allowing you to define additional mappings or configurations.
- Template configuration: Offers template configuration using the Freemarker template engine, allowing you to customize the generated code templates.
- Strategy configuration: Allows you to configure naming strategies, such as converting table and column names from underscore to camel case, enabling Lombok annotations for entity classes, and generating RESTful controllers.
- Output configuration: Enables custom output configuration, allowing you to specify the output file paths for generated code files.
- Code generation: Executes the code generation process based on the specified configurations, generating the desired code files according to the provided table names and database schema.

## Prerequisites

- Java Development Kit (JDK) installed
- Spring Boot framework set up
- Database connection details (URL, driver, username, and password)

## Getting Started

1. Clone or download the code generator project to your local machine.
2. Open the project in your preferred Java IDE.
3. Configure the project's dependencies and ensure all required libraries are available.
4. Modify the database connection details in the `DataSourceConfig` class to match your database setup.
5. Customize the package configuration in the `PackageConfig` class to suit your project's package structure.
6. Review and modify the strategy configuration in the `StrategyConfig` class based on your naming conventions and requirements.
7. Execute the `main` method in the `Generator` class to start the code generation process.
8. Follow the prompts in the console to enter the table names for which you want to generate code.
9. Once the code generation process is complete, the generated code will be available in the specified output directory.

## Customize Templates

You can customize the generated code templates by modifying the template files in the `/templates` directory. These templates are written in the Freemarker template language and follow a specific structure. You can update the templates to match your desired code style or add additional functionality as needed.

## Conclusion

The Java Spring Boot code generator simplifies the process of generating boilerplate code for your application. By configuring the necessary settings and providing the required input, you can quickly generate entities, controllers, services, and data access layers, reducing manual coding efforts and improving development efficiency.

Feel free to explore the project, customize the templates, and adapt it to your specific project requirements.