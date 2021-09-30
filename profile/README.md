<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://guides.github.com/features/mastering-markdown/)
-->

# Hello Friends!

### [Visit the private GitHub Pages site for this organization](https://urban-tribble-c7dc028f.pages.github.io/)

Ping Kery/Nick/Cathay if you don't have the appropriate level of access you need for this organization.

Visit the [Docs Repository here](https://github.com/Sage-CRE/docs)!

### GitHub Actions

Most of our CI/CD is done through [GitHub Actions](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions).

[Example here](https://github.com/Sage-CRE/nebula-ui/tree/main/.github/workflows)

### IDE

Although we don't enforce any particular IDE on the team, we have found the team generally uses one of two tools primarily (and thus upkeeps configurations for those tools)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/preview/vs2022/)
- [Visual Studio 2019](https://visualstudio.microsoft.com/vs/)

Subscription may need to be requested through Kery/Nick for Professional/Enterprise editions of these tools.

### Documentation

The team has [a central docs repository](https://github.com/Sage-CRE/docs) wherein we try to keep up standards and decisions we've made along the way. 

### Docker/Docker Compose

We use Docker and Docker Compose to simplify developer workstation requirements/processes
E.g. - Nebula UI uses [Docker Compose](https://github.com/Sage-CRE/nebula-ui/blob/main/docker-compose-wiremock.yml) to spin up a wiremock instance as part of our Contract First approach to development. 

E.g. - General Ledger Service uses Docker Compose to spin up a PostgreSQL instance with the latest schema for local development. https://github.com/Sage-CRE/general-ledger-service/blob/main/docker-compose.yml

### PostgreSQL

Our data storage is primarily done through Postgres.

[Docs repository](https://github.com/Sage-CRE/docs/tree/main/Postgres)

### React

Our primary UI technology of choice is React.

[Docs repository](https://github.com/Sage-CRE/docs/tree/main/UI)

### .NET/C#

Our APIs are largely written in C# leveraging .NET 5.

[Docs repository](https://github.com/Sage-CRE/docs/tree/main/APIs)

### Storybook

- [Storybook Repository](https://github.com/Sage-CRE/react-playground)
- [Deployed Storybook instance](https://nebula-storybook.azurewebsites.net/)
- [Docs](https://github.com/Sage-CRE/docs/tree/main/UI#storybook)

### WireMock

We use a Contract First approach to development which allows the API contract to be the first target for development. The UI and API can both work simultaneously against the specified contract while the UI targets Wiremock and eventually shifts to the API.

- [Docs repository](https://github.com/Sage-CRE/docs/tree/main/UI#wiremock)

### Azure

- If you're interested in Azure certifications sign up [here](https://esi.microsoft.com/).
- [Naming Practices](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming)
- [AZ CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
- [Azure Powershell](https://docs.microsoft.com/en-us/powershell/azure/install-az-ps?view=azps-6.3.0)
- [Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview)
- [Azure Key Vault](https://docs.microsoft.com/en-us/azure/key-vault/general/overview)
- [Azure Logic App](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-overview)
- [Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/quickstart-dotnetcore?tabs=netcore31&pivots=development-environment-vs)
- [Docs repository](https://github.com/Sage-CRE/docs/tree/main/Azure)
