# Alphastream Content Intelligence Postman Collections

Welcome to our Content Intelligence (CI) Postman Collections Quickstart Guide! This guide provides you a quick way to get started with the CI API of Alphastream.

For Quickstart guides to our other API endpoints, see the [Alphastream Quickstart](https://github.com/alphastream/quickstart).

## Getting started

> Check out our [Alphastream Content Intel in Three Minutes](https://www.powtoon.com/s/fx2T4kVzNH2/1/m/s) and here is a [Quick Postman Demo in 90 Seconds](https://www.loom.com/share/772dcb7ca7864c5caf9540497f7bde6d) video tutorial.

[![Watch the demo video](https://github.com/raj-alphastream/postman1/blob/af3c6d6aa11f7eae997abdcb8d376c52cadae54d/images/Postman-demo-img.png)](https://www.loom.com/share/772dcb7ca7864c5caf9540497f7bde6d)


### Sample examples to get started

Here are 4 examples of how you can use these API endpoints that will be included in the CI Postman collection. 

•Content Trends:
 1. Analysis example – how many tweets on an entity was published in last 24-hrs and was any anomaly detected? 
 2. Discovery example – what are the top-5 most spoken about entities in the last 3 days? 
 
 ![[plaid-postman-configuration]](https://github.com/raj-alphastream/postman1/blob/d73fcd7658909e298ff60a93f82a7dc9c24d7877/images/Trends%20Analysis.PNG))(/images/Trends Discovery.PNG)

![[plaid-postman-configuration]](https://github.com/raj-alphastream/postman1/blob/98887f7edd33d07d88b889acd75d93fa75f972d3/images/Trends%20Discovery.PNG)(/images/Trends Discovery.PNG)

•Content Coverage:
Coverage by content volume within a specific sector/ sub-sector (Financial)

•Source & Author Analytics:
Which content (data) source has published the highest volume of content in past day/ week and how it changed over time?
Which content (author) source has published the highest volume of content in past day/ week and how it changed over time?

Follow these steps to quickly get started with the [AS APIs](https://api-docs.alphastream.io/):

1. [Contact Us](https://alphastream.io/contact/) to get a set of API keys that are required for interacting with the API if you do not already have them.
2. Click the "Run in Postman" button below.

https://web.postman.co/network/import?collection=16904982-d2ecc9ee-6281-45a6-bb3f-1d82b891ec4e-U16jPSJe&referrer=https%3A%2F%2Fapi-docs.alphastream.io%2F%23237262a9-e85b-4398-a491-e34efe126a84&versionTag=latest&environment=10022312-614ac5be-ff90-40d8-bd62-b963270eaa36-U16jPSJe&traceId=undefined

([![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/5b25e16aa557c7cf8e31?action=collection%2Fimport#?env%5BSandbox%5D=W3sia2V5IjoiY2xpZW50X2lkIiwidmFsdWUiOiJZT1VSX0NMSUVOVF9JRCIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJ0ZXh0In0seyJrZXkiOiJzZWNyZXRfa2V5IiwidmFsdWUiOiJZT1VSX1NFQ1JFVF9LRVkiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoic2VjcmV0In0seyJrZXkiOiJwdWJsaWNfdG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJ0ZXh0In0seyJrZXkiOiJhY2Nlc3NfdG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJ0ZXh0In0seyJrZXkiOiJhc3NldF9yZXBvcnRfdG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJ0ZXh0In0seyJrZXkiOiJlbnZfdXJsIiwidmFsdWUiOiJzYW5kYm94LnBsYWlkLmNvbSIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJ0ZXh0In0seyJrZXkiOiJhY2NvdW50X2lkIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoidGV4dCJ9LHsia2V5IjoicHJvY2Vzc29yX3Rva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoidGV4dCJ9LHsia2V5IjoidHJhbnNmZXJfaWQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJ0ZXh0In0seyJrZXkiOiJ1c2VyX3Rva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoidGV4dCJ9LHsia2V5IjoidXNlcl9pZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6InRleHQifV0=))

3. Once both the collection and the environment variables are imported into Postman, see the [Configuration](https://github.com/postman#configuration) section on how to correctly configure API keys with the collection.

### Configuration

The AS Postman collection uses [Postman environment variables](https://learning.getpostman.com/docs/postman/environments_and_globals/intro_to_environments_and_globals/) to simplify each API request.

![plaid-postman-configuration](/images/plaid-postman-config.png)

1. Select the `API-Insights` environment in the top right corner
2. Click the `eye` icon to open the environment settings
3. Copy in your [API keys from your CI Dashboard](https://dashboard.alphastream.io/account/keys), into each field:

- `client_id`
- `client_secret`

4. Save your changes and start making API requests!

## Quickstart

Once you have completed the steps in the Configuration section above, you are ready to make API requests using Postman! The following steps are a quick walkthrough to making an API request. In this example, we will use the special capabilities of the Insights-API test environment to bypass any client-side Link UI and make all of our requests via the backend.

1. Make sure the "Collection" pane is selected, then expand the "Insights API Endpoints" folder on the left and navigate to API Endpoints -> Items -> Item Creation -> Create Item [Sandbox Only].
2. In the pane on the right, which has the options "Params", "Authorization", "Headers" etc. click on the "Body" tab.
3. (Optional) If you want, update the product under `initial_products` to match the product or use case example you would like to try, such as "Content Trends" or "Content Coverage".
4. Click the blue "Send" button on the right.
5. The response body should appear in Postman. The `bearer_token` returned should be entered for any subsequent API calls.
6. /OR -Select the "Exchange token" endpoint, click on the "Body" tab, then hit "Send". An `access_token` will be returned and will automatically be used in our next request.
7. Select any product endpoint of your choice. If you are not sure which one to use, a good simple example is "Basic Histogram". Expand the product endpoint folder and click on the endpoint you would like to use ("View Histogram Data", if you are using this one).
8. Click on the "Body" tab. Complete any other required fields (for this example, there are none) and click "Send".
9. You will receive a response containing your requested data!

## Making Postman calls with real data in Production or Development

Can be done via Postman OR for reasons of security with specific client data cannot be done entirely via Postman API calls? 

The response will contain an `access_token` suitable for making calls in Production (or Development)! As in the Quickstart, it will be automatically saved for you to use in future requests. You can then follow the same steps as you did in the Quickstart (starting with step 6) to make API requests for real data.

## Useful Resources

<< Link to AS Content Intel Folder >>

## How to use the Data to develop your Content INTEL Dashboard

You can develop your insights dashboard by importing the data into a tool like PowerBI. 

This is an EX. only... https://community.powerbi.com/t5/Data-Stories-Gallery/Stock-Market-Dashboard/td-p/1328610 

 ![[bi-config]](https://github.com/raj-alphastream/postman1/blob/5b9b00bb4ff74c7219479881a41224a224f0ed56/images/CI-dashboard-ex.png)(/images/ex-1.PNG)

Want to learn more? [Contact Us](https://alphastream.io/contact/) to request a custom analytics project with Alphastream. 
