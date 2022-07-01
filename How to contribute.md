This documentation is primarily aimed at AS employees who would like to edit the collection. For instructions on using the collection, see the README.

#### Editing the AS Postman collection
The easiest way to edit the collection is to edit your own local copy of the collection using the Postman app. After downloading it, you can open the Plaid Postman collection and make edits. This is a pretty intuitive process, with a few things to be aware of:

Make sure to use the "tests" tab of the collection when appropriate to save values that will be used as input to other API calls. For example, when calling `/link/token/create`, we have the following under "tests":

```
let response = pm.response.json();
linkToken = response.link_token;
pm.environment.set("link_token", linkToken);
```

This code allows other API calls to reference ``{{link_token}}`` in the request body rather than requiring the user to copy and paste the Link token.

Make sure to rename examples to "OK" rather than using the default name.

#### Publishing the AS Postman collection

**Important: Before you publish the collection, make sure to clear the values of all environment variables except XYZ.**

When you are ready to publish the collection, do the following:

Leif to contribute
