# Fabric Pipeline Definition

`pl_incremental_ingestion.json` is a sanitized copy of the Microsoft Fabric pipeline export.

Execution order: `NB_Incremental_bronze` → `NB_Incremental_Silver` → `NB_Incremental_Gold`, with Succeeded dependencies.

## Before deployment
Replace each `REPLACE_WITH_*` placeholder with the notebook and workspace IDs for your own Fabric environment. This export is a reference template and is **not deployable unchanged**. Verify the import/deployment method supported by your Fabric environment.

The pipeline schedule is not included in this JSON export. Configure daily 9:00 AM IST scheduling separately in Fabric. Do not commit credentials or private source data.
