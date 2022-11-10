# Data source basics

Data source is where you manage credentials and make connections to various popular databases such as PostgreSQL, MongoDB, Elasticsearch and all kinds of internal or third party APIs.&#x20;

Openblocks stores your credentials securely and does not store any data from your requests or responses. It only serves as a proxy between client side and your data sources.

## Connect to a new data source

{% hint style="info" %}
Check out [IP allowlist](ip-allowlist.md) and add Openblocks IP addresses to your data source allowlist when needed.
{% endhint %}

Follow the steps below:

1. Click **Data Sources** on Openblocks homepage.
2.  Click **New data source** on the upper right. This permission is restricted to workspace admins and developers.

    <figure><img src="../.gitbook/assets/screenshot-20221109-190716.png" alt=""><figcaption></figcaption></figure>
3. Select the database or API type you need to connect.
4. Fill out data source connection fields. See docs in [Connect to databases](connect-to-databases/) and [Connect to APIs](connect-to-apis/) for detailed tutorials.
5. Click **Test the connection** to check whether you can make a successful connection to data source based on current settings.
6. Click **Save**.

You can also connect to a new data source when creating or editing queries in query library or query editor.

\[pic]+caption

\[pic]

## Permissions

In Openblocks, members with permissions to create, edit, delete and use data sources **** are listed as follows:

* **Create:** workspace admins and developers
* **Edit** or **Delete:** data source creators and workspace admins
* **Use**: workspace admins and developers

In particular, members with permissions to edit an app are automatically granted access to use existing data sources in the app.\
\
\
