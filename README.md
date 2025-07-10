# Azure Data Factory – Week 6 Assignment

This project demonstrates the use of Azure Data Factory to securely extract data from on-premise and FTP sources, perform incremental loads, and schedule automated pipeline executions. It also incorporates retry logic to improve fault tolerance and resilience.

# Objectives Covered

- Configure **Self-hosted Integration Runtime (SHIR)** to extract data from a local SQL Server.
- Connect to an **SFTP Server** to extract files using linked services.
- Create and execute a **Copy Data Pipeline** using both sources.
- Add **Incremental Load** logic using parameters (e.g., `LastRunDate`).
- Automate pipeline using a **Monthly Trigger** (e.g., Last Saturday).
- Implement **Retry Logic** to handle transient failures gracefully.
