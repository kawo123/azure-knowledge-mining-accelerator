# Azure Knowledge Mining Solution Accelerator

Solution accelerator for Azure knowledge mining use cases using [Azure Cognitive Search](https://docs.microsoft.com/en-us/azure/search/search-what-is-azure-search).

---

## Getting Started

**WARNING**: Please do not commit Azure secrets to GitHub

- For setup instructions of cracking travel collateral documents through Azure Portal, please see [this](./doc/instructions.md)

- For scripted setup, follow the below steps
  - Launch Azure Cloud Shell in bash and clone this repo
  - Execute `AZ_SUBSCRIPTION_ID='<subscription-id>' AZ_BASE_NAME='<base-name>' ./scripts/setup.sh`

- For additional examples of Azure Cognitive Search features, download [Postman](https://www.postman.com/downloads/) and import Postman collection & environment under `./postman`. The Postman collection contains RESTful APIs which demonstrate additional Azure Cognitive Search features.

## Public Demos

- [COVID-19 Medical Research Search](https://covid19search.azurewebsites.net/): Search engine for COVID-19 related research papers

- [Wolters Kluwer](https://wolterskluwereap.azurewebsites.net/): Empowers attorneys to search across Securities and Exchange Commission (SEC) filings and correspondence between public companies and the SEC

- [JFK Files](https://jfk-demo.azurewebsites.net/): Enable people to search through multi-media and handwritten contents related to JFK assassination and explore the relationship between different entites ([video link](https://www.youtube.com/watch?v=XRI0DnjAgmo))

- [Job Portal](https://azjobsdemo.azurewebsites.net/): Enable people to search for NYC jobs based on titles, geo-locations, and salary

## References

- [Azure Cognitive Search concepts and features](./doc/concepts.md)

- [Azure Cognitive Search Enterprise Readiness Checklist](./doc/enterprise_readiness.md)

- [Azure Cognitive Search: Built-in Skills](https://docs.microsoft.com/en-us/azure/search/cognitive-search-predefined-skills)

- [Github | Azure | Azure Cognitive Search Sample Custom Skills](https://github.com/Azure-Samples/azure-search-power-skills)

- [Github | Azure | Azure Cognitive Search Sample Data](https://github.com/Azure-Samples/azure-search-sample-data)

- [Github | Azure | Azure Cognitive Search Workshop](https://github.com/Azure-Samples/azure-search-knowledge-mining)

## TODO

- Build pipeline for different types of data (healthcare research paper, media image, manufacturing field note)
- create postman collection to demo boosting/autocomplete/suggestion
- reporting
- sanitize credentials

---

### PLEASE NOTE FOR THE ENTIRETY OF THIS REPOSITORY AND ALL ASSETS

1. No warranties or guarantees are made or implied.
2. All assets here are provided by me "as is". Use at your own risk. Validate before use.
3. I am not representing my employer with these assets, and my employer assumes no liability whatsoever, and will not provide support, for any use of these assets.
4. Use of the assets in this repo in your Azure environment may or will incur Azure usage and charges. You are completely responsible for monitoring and managing your Azure usage.

---

Unless otherwise noted, all assets here are authored by me. Feel free to examine, learn from, comment, and re-use (subject to the above) as needed and without intellectual property restrictions.

If anything here helps you, attribution and/or a quick note is much appreciated.
