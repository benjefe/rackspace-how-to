---
permalink: rackspace-cloud-sites-essentials-mysql-databases/
node_id: 58
title: Rackspace Cloud Sites Essentials - MySQL Databases
type: article
created_date: '2011-02-28'
created_by: Rackspace Support
last_modified_date: '2015-12-29'
last_modified_by: Stephanie Fillmon
product: Cloud Sites
product_url: cloud-sites
---

**Note:** This article is written for our [Cloud Sites Control Panel](https://manage.rackspacecloud.com/). You can get to it from the [Cloud Control Panel](https://mycloud.rackspace.com) by clicking **Rackspace Cloud** in the upper-left corner and selecting **Cloud Sites**. You can also navigate directly to <https://manage.rackspacecloud.com/>.

### Previous section

[Cloud Sites introduction](/how-to/cloud-sites)

This article shows you how to add a MYSQL database to your website
through Cloud Sites. Follow the steps below:

-   Log into the [Rackspace Cloud Control Panel](http://manage.rackspacecloud.com)
-   Navigate to **Hosting > Cloud Sites**
-   Click on the **domain name** you would like to add your database to
-   From the domain details view, click the **Features** tab

    <img src="{% asset_path cloud-sites/rackspace-cloud-sites-essentials-mysql-databases/featurestab.png %}" alt="" />

-   In the Databases section, click **Add**.

    <img src="{% asset_path cloud-sites/rackspace-cloud-sites-essentials-mysql-databases/adddatabase.png %}" alt="" />

  **Note:** If the Add button is not visible, then the database feature
can be added by allowing at least one database on your site. For more
Cloud Sites help, see the [Cloud Sites support page](/how-to/cloud-sites).

  As long as you have the **Add** button, as shown above in the
screenshot, then you are good to proceed

-   Next, enter a database name identifier in the **Database Name**
    field
-   Select a database type from the **Database Type** and press
    **Continue** to proceed

    <img src="{% asset_path cloud-sites/rackspace-cloud-sites-essentials-mysql-databases/databasename.png %}" alt="" />

  **Note:** The prefix of the database name is generated for the user by
Cloud Sites. The database name is a combination of the prefix and the
identifier.

-   Next, enter a database user identifier in the **Database Username**
    field

-   Enter a password in the **Password** field and confirm the password
    by reentering it in the **Confirm Password** field and then click
    **Finish**

    <img src="{% asset_path cloud-sites/rackspace-cloud-sites-essentials-mysql-databases/databaseuser.png %}" alt="" />

  **Note:** The prefix of the database user name is generated by Cloud
Sites. The database user name is a combination of the prefix and the
identifier.

-   A clock icon is displayed while the database completes the setup.
    Click the Features tab to refresh the status.

    <img src="{% asset_path cloud-sites/rackspace-cloud-sites-essentials-mysql-databases/pendingdatabase.png %}" alt="" />

-   Confirm that the new database is active by verifying that the
    Status column has a green check mark icon to the left of the
    database name.

    <img src="{% asset_path cloud-sites/rackspace-cloud-sites-essentials-mysql-databases/databaseready.png %}" alt="" />

  **Note:** If your database does not have a green check next to in in
excess of ten minutes and you are still experiencing a problem, please
do not hesitate to contact our technical support 24x7 by phone, chat, or
by submitting a ticket through your Control Panel.

You have added a MySQL database to your website. Users can now start
working with the new MySQL database.

In the next article we will learn how to work with your new database
through our online MySQL database interface.

### Next section

[PHPmyAdmin database management interface](/how-to/rackspace-cloud-sites-essentials-phpmyadmin-database-management-interface)
