# Direct Lake semantic model

Extracted TMDL view scripts for `sm_incremental_sales_analytics`. Three pre-aggregated Gold tables, one shared expression, no explicit measures or relationships. These are createOrReplace scripts, not a complete deployable PBIP project.

To adapt in a separate Fabric model, create the Gold tables first, replace the endpoint and database placeholders in DatabaseQuery with your own values, configure authentication, and review the expression and table scripts before applying (expression first). Do not apply to the original production model. Deployment has not been tested. Lineage tags are preserved from the extracted scripts.
