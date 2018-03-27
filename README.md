# DnA Transformation Engine
The DnA (Data and Analytics) Transformation Engine is a JSON config-driven engine for transforming data into target structures. The application is written in C# and runs on Azure Functions.

## Repository Structure
----
The repository is split into multiple high-level folders:
### ARMTemplates
This folder holds the ARM templates for the project. These templates define the Azure resources required to run the Transformation Engine application. The templates are meant to be comprehensive, meaning that there is no manual intervention required to create or duplicate the resources.

### DataTransformationEngine
This folder contains C# libraries related to the Transformation Engine project. The package is meant to be built and deployed to the Azure Functions App to support the Functions themselves.

### FunctionApp
This folder contains the C# code that runs directly in Azure Functions. The code is structured such that every function has it's own folder, with the required artifacts located therein.

### PS1
This folder contains PowerShell code to support the application, mainly the build and release process.


## Build/Release Strategy
---
TODO: Define and add build/release strategy

## Local Development
----
TODO: Add steps 