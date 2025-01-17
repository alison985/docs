- [Home](/)
- **Getting Started**
- [Administrator](getting-started/Admin/)
  - [Account Pre-reqs](getting-started/Admin/create-account.md)
  - [Configure Airflow](getting-started/Admin/configure-airflow.md)
  - [Creating Airflow Dags](getting-started/Admin/creating-airflow-dags.md)
  - [User Management](getting-started/Admin/user-management.md)
- [Developer](getting-started/developer/)
  - [Snowflake Extension](getting-started/developer/snowflake-extension.md)
  - [Transform Tab](getting-started/developer/transform-tab.md)
  - [Working with dbt in Datacoves](getting-started/developer/working-with-dbt-datacoves.md)
  - [Using Git](getting-started/developer/using-git.md)
- **Diving Deeper**
- [How to](/how-tos/)
  - [Airflow](/how-tos/airflow/)
    - [Initial setup](/how-tos/airflow/initial-setup.md)
    - [Run dbt](/how-tos/airflow/run-dbt.md)
    - [Generate DAGs from yml](/how-tos/airflow/generate-dags-from-yml.md)
    - [Calling External Python Scripts](/how-tos/airflow/external-python-dag.md)
    - [Use Variables and Connections](/how-tos/airflow/use-variables-and-connections.md)
    - [Dynamically Set Schedule](/how-tos/airflow/dynamically-set-schedule.md)
    - [Run Airbyte sync jobs](/how-tos/airflow/run-airbyte-sync-jobs.md)
    - [Run Fivetran sync jobs](/how-tos/airflow/run-fivetran-sync-jobs.md)
    - [Add Dag Documentation](how-tos/airflow/create-dag-level-docs.md)
    - [Send Emails](/how-tos/airflow/send-emails.md)
    - [Send Microsoft Teams notifications](/how-tos/airflow/send-ms-teams-notifications.md)
    - [Send Slack notifications](/how-tos/airflow/send-slack-notifications.md)
    - [Get Current Branch Name from a DAG Task](/how-tos/airflow/get-current-branch-name.md)
    - [Custom Worker Environment](/how-tos/airflow/customize-worker-environment.md)
    - [Request Memory and CPU](/how-tos/airflow/request-resources-on-workers.md)
  - [VS Code](/how-tos/vscode/)
    - [Initial Configuration](/how-tos/vscode/initial.md)
        - [BigQuery](/how-tos/vscode/bigquery_setup.md)
        - [Databricks](/how-tos/vscode/databricks_setup.md)
        - [Redshift](/how-tos/vscode/redshift_setup.md)
        - [Snowflake](/how-tos/vscode/snowflake_setup.md)
    - [Override VS Code settings](/how-tos/vscode/override.md)
    - [Reset User Env](/how-tos/vscode/reset-user-env.md)
  - [Datacoves](/how-tos/datacoves/)
    - [Configure Connection Templates](/how-tos/datacoves/how_to_connection_template.md)
    - [Configure Environments](how-tos/datacoves/how_to_environments.md)
    - [Configure Groups](how-tos/datacoves/how_to_groups.md)
    - [Configure Integrations](how-tos/datacoves/how_to_integrations.md)
    - [Configure Invitations](how-tos/datacoves/how_to_invitations.md)
    - [Configure Projects](how-tos/datacoves/how_to_projects.md)
    - [Configure Service Connections](how-tos/datacoves/how_to_service_connections.md)
    - [Manage Users](/how-tos/datacoves/how_to_manage_users.md)
    - [Update Repository](getting-started/Admin/configure-repository.md)
  - [Superset](/how-tos/superset/)
    - [Add a Database](how-tos/superset/how_to_database.md)
    - [Add a Data Set](how-tos/superset/how_to_data_set.md)
  - [DataOps](/how-tos/dataops/)
    - [Releasing a new feature](/how-tos/dataops/releasing-new-feature)
  - [Git](/how-tos/git/)
    - [SSH Keys configuration](/how-tos/git/ssh-keys)
  - [Snowflake](/how-tos/snowflake/)
    - [Warehouses, Schemas and Roles](/how-tos/snowflake/warehouses-schemas-roles)
- [Explanation](/explanation/)
  - [Best Practices](explanation/best-practices/)
    - [Datacoves](explanation/best-practices/datacoves/)
      - [Folder Structure](explanation/best-practices/datacoves/folder-structure)
    - [dbt](explanation/best-practices/dbt/)
      - [dbt Guidelines](explanation/best-practices/dbt/dbt-guidelines)
      - [Object Naming Standards](explanation/best-practices/dbt/object-naming)
      - [What are Inlets, Bays, and Coves](explanation/best-practices/dbt/inlets-bays-coves)
    - [Git](explanation/best-practices/git/)
    - [Snowflake](explanation/best-practices/snowflake/)
      - [Security Model](explanation/best-practices/snowflake/security-model)
      - [GDPR and Time-Travel](explanation/best-practices/snowflake/time-travel)
- [Tutorials](/tutorials/)
- [Reference](/reference/)
  - [Administration Menu](reference/admin-menu/)
    - [Account Settings & Billing](reference/admin-menu/settings_billing.md)
    - [Connection Templates](reference/admin-menu/connection_templates.md)
    - [Environments](reference/admin-menu/environments.md)
    - [Groups](reference/admin-menu/groups.md)
    - [Integrations](reference/admin-menu/integrations.md)
    - [Invitations](reference/admin-menu/invitations.md)
    - [Projects](reference/admin-menu/projects.md)
    - [Service Connections](reference/admin-menu/service_connections.md)
    - [Users](reference/admin-menu/users.md)
  - [Airflow](reference/airflow/)
    - [Airflow Config Defaults](reference/airflow/airflow-config-defaults.md)
    - [DAG Generators](/reference/airflow/dag-generators.md)
    - [Datacoves Operators](reference/airflow/datacoves-operator.md)
  - [Datacoves](reference/datacoves/)
    - [Datacoves SLA](reference/datacoves/sla.md)
  - [VS Code](reference/vscode/)
    - [Datacoves Environment Variables](reference/vscode/datacoves-env-vars.md)
  - [Metrics & Logs](reference/metrics-and-logs/)
    - [Grafana](reference/metrics-and-logs/grafana.md)
  - [Security](/reference/security/)
- **Monitoring**
- [Datacoves Status Tracker](https://datacoves.statuspage.io/)
  
<footer id="mb-footer"></footer>
