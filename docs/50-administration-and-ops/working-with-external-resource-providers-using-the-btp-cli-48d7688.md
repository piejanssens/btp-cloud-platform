<!-- loio48d7688f166642dca0c431f55d1d141f -->

# Working with External Resource Providers Using the btp CLI

Use the SAP BTP command line interface \(btp CLI\) to get details, or to create or delete resource provider instances in a global account.

> ### Note:  
> The use of this functionality is subject to the availability of the supported non-SAP cloud vendors in your country or region.

Creating a resource provider instance allows your global account to connect to your provider account on a non-SAP cloud vendor. Through this channel, you can then consume remote service resources that you already own and which are supported by SAP BTP.


<table>
<tr>
<th valign="top">

Task



</th>
<th valign="top">

Run the command...



</th>
</tr>
<tr>
<td valign="top">

List all resource provider instances in a global account



</td>
<td valign="top">

`btp list accounts/resource-provider`



</td>
</tr>
<tr>
<td valign="top">

Get details about a resource provider instance



</td>
<td valign="top">

`btp get accounts/resource-provider`



</td>
</tr>
<tr>
<td valign="top">

Create a resource provider instance



</td>
<td valign="top">

`btp create accounts/resource-provider`



</td>
</tr>
<tr>
<td valign="top">

Update a resource provider instance



</td>
<td valign="top">

`btp update accounts/resource-provider`



</td>
</tr>
<tr>
<td valign="top">

Delete a resource provider instance



</td>
<td valign="top">

`btp delete accounts/resource-provider`



</td>
</tr>
</table>

For more information, see [Managing Resource Providers](managing-resource-providers-e2c250d.md).

**Related Information**  


[Working with Global Accounts, Directories, and Subaccounts Using the btp CLI](working-with-global-accounts-directories-and-subaccounts-using-the-btp-cli-85a683e.md "Use the SAP BTP command line interface (btp CLI) to manage operations with global accounts, directories, and subaccounts.")

[Setting Entitlements Using the btp CLI](setting-entitlements-using-the-btp-cli-5af849c.md "Use the SAP BTP command line interface (btp CLI) to set entitlements to define the functionality or permissions available for users of global accounts, directories, and subaccounts.")

[Working with Environments Using the btp CLI](working-with-environments-using-the-btp-cli-48db155.md "Use the SAP BTP command line interface (btp CLI) to manage runtime environment instances in a subaccount. For example, enable the Cloud Foundry environment by creating a Cloud Foundry org (environment instance).")

[Working with Multitenant Applications Using the btp CLI](working-with-multitenant-applications-using-the-btp-cli-c1b0fcc.md "Use the SAP BTP command line interface (btp CLI) to manage the multitenant applications to which a subaccount is entitled to subscribe.")

[Managing Users and Their Authorizations Using the btp CLI](managing-users-and-their-authorizations-using-the-btp-cli-94bb593.md "User authorizations are managed by assigning role collections to users (for example, Subaccount Administrator). Use the SAP BTP command line interface (btp CLI) to manage roles and role collections, and to assign role collections to users.")

[Working With Resources of the SAP Service Manager Using the btp CLI](working-with-resources-of-the-sap-service-manager-using-the-btp-cli-fe6a53b.md "Use the SAP BTP command line interface to perform various operations related to your platforms, attached service brokers, service instances, and service bindings.")
