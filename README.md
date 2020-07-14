# Delivery Service API

This is a draft api between the transport system  and external delivery services.  

The api describes: 

- Query and filter existing deliveries 


### The API definition is located at spec/spec.yaml

___

### View the API with Swagger Tools
```
cd [absolute-repo-path]
docker run -p 9090:8080 -e SWAGGER_JSON=/spec.yaml -v $(pwd)/spec/spec.yaml:/spec.yaml swaggerapi/swagger-ui
```
- Open Browser `http://localhost:9090`

___

### Edit the API with Swagger Tools
```
cd [absolute-repo-path]
docker run -p 9091:8080 swaggerapi/swagger-editor
```

- Open Browser `http://localhost:9091`
- Choose delivery-service-api/spec/spec.yaml using `File / Import file` 
- Edit the specification
- Export the specification and commit the replaced `delivery-service-api/spec/spec.yaml` file

___

### OpenAPI Specification
- https://swagger.io/resources/open-api/
- https://swagger.io/specification/

___

This repository is maintained and the api is designed by 

<a href="http://elderbyte.com"><img height=50px src="docs/logos/elderbyte.png"></a>  
<a href="https://www.acs-ag.com"><img height=30px src="docs/logos/acs.png"></a>
