# Define Custom Domain for your API Gateway 

Custom domain names are simpler and more intuitive URLs that you can provide to your API users.

After deploying your API, you can invoke the API using the default base URL of the following format:

```sh
 [Without custom domain]
 https://api-id.execute-api.region.amazonaws.com/YourStage/Route
 
 [With custom domain]
 https://YourDomain/Route
 
```

Not only will custom domain help you have a simplifed URL to invoke API Gateway, but also you will have a consistent URL even if API Gateway is created. 
