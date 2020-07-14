# Delivery Service API

This is a draft api between the transport system  and external delivery services.  

The api describes: 

- Query and filter existing deliveries 
- Upsert deliveries
- Delete existing deliveries


### The API definition is located at spec/spec.yaml

___

### View the API with Swagger Tools
```
cd [absolute-project-path]
docker run -p 9090:8080 -e SWAGGER_JSON=/spec.yaml -v $(pwd)/spec/spec.yaml:/spec.yaml swaggerapi/swagger-ui
```
- Open Browser `http://localhost:9090`

___

### Edit the API with Swagger Tools
```
cd [absolute-project-path]
docker run -d -p 9091:8080 -v $(pwd)/spec:/usr/share/nginx/html/delivery-services swaggerapi/swagger-editor
```

- Open Browser `http://localhost:9091`
- Import URL /delivery-services/spec.yaml
- Edit the spec
- Export the file and commit under spec/spec.yaml

___

### OpenAPI Specification
- https://swagger.io/resources/open-api/
- https://swagger.io/specification/

___

The repository is maintained by 

<a href="http://elderbyte.com"><img height=50px src="docs/logos/elderbyte.png"></a>  
<a href="https://www.acs-ag.com"><img height=30px src="docs/logos/acs.png"></a>