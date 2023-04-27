# Connection Templates Admin

## Overview

A Connection Template in Datacoves defines the basic information for your data warehouse. It acts as a template that can then be used for user and service connections. This simplifies the onboarding process for users.

## Connection Templates Listing

![Connections Listing](./assets/connections_landing.png)

On the Connection Templates landing page you can see a list of Connection Templates associated with each of your Datacoves projects.

For each template we can see the provider (i.e. Snowflake, Redshift) and the number of service and user accounts associated with each template.

Each row contains 2 action buttons, Edit and Delete.

## Create/Edit Connection Template

To create a new connection template click the `Create Connection Template` button.

![Connections Create or Edit Page](./assets/connections_editnew_page.png)

Each Connection Template consist of the following fields:

- **Name** This is the name users will see when selecting the base connection template when entering credentials for themselves or service accounts.
- **Enabled for users** This flag indicates whether this template will be available for users or only for service accounts. To simplify the end-user experience, it is best to show them only the primary template they should use when entering their credentials. If enabled, a new field will appear:

  - **User field configuration** Defines how the DB connection `Username` field will be treated. It can be `provided` by the end-user or inferred using two strategies: from his/her email, or based on templates.
    The difference in these approaches will be noticed when the final user creates their respective connections in `Settings -> Database connections`

    - **Provided by user** With this strategy, the user will have free access to write the desired username when creating a connection

      ![Provided by user](./assets/connectiontemplates_provided_by_user.png)

      > **Note**<br>
      > We suggest not using the user-provided username if snowflake public key is added by datacoves

    - **Inferred from user's email** Defines the username field as read-only, pre-populating it with the user's email username (what comes before @domain.com)
      ![Inferred from email](./assets/connectiontemplates_inferred_from_email.png)
    - **Inferred from user info using a custom template** With this last approach, you can choose a template from which the username will be generated. If selected a new field will appear to select one of those.
      ![Inferred from template](./assets/connectiontemplates_inferred_from_template.png)
      At this moment we only support our provided `Connection username for admins` template. With this template, the username will see `admin_{{username}}` when creating a DB connection.
      ![Username from template](./assets/connectiontemplates_username_from_template.png)

- **Project** This defines the Datacoves project that should be associated with this connection template
- **Type** Defines the data warehouse provider so that users are presented the appropriate fields when entering their credentials.
- **Provider connection details** Based on the Provider Type selected, available default parameters will be displayed.
  - For Snowflake, the available fields are: `Account`, `Warehouse`, `Database`, and `Role`
    ![Snowflake Connection Type](./assets/connections_editnew_snowflake.png)
  - For Redshift, the available fields are: `Host` and `Database`
    ![Redshift Connection Type](./assets/connections_editnew_redshift.png)