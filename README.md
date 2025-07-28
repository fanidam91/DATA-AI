DATA-ai/
├── dev/     # Development notebooks and experimental code
├── test/    # QA-validated notebooks, ready for UAT or integration testing
├── prod/    # Production-ready notebooks, pipelines, and integration scripts
Each folder supports a stage of the Data Factory + Databricks development lifecycle:

dev/: Initial development of notebooks, transformation logic, and orchestration code. Typically connected to DEV ADF pipelines for iterative testing and debugging.

test/: Contains stable versions of notebooks that have passed unit and functional testing. These are linked with TEST ADF environments for validation and QA.

prod/: Includes final notebooks and scripts approved for deployment in production. Tied to PROD Data Factory pipelines and production-grade Delta Lake tables.

💡 This structure supports CI/CD and version control across ADF environments while maintaining clean separation between development, testing, and production workflows.
