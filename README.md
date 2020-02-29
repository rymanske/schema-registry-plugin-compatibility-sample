## Schema Registry Plugin Compatibility Check Sample

This sample project demonstrates:
- Generating Avro schemas from Avro IDL files using [davidmc24/gradle-avro-plugin](https://github.com/davidmc24/gradle-avro-plugin)
and 
- Verifying the compatibility of those schemas in Confluent Schema Registry using [ImFlog/schema-registry-plugin](https://github.com/ImFlog/schema-registry-plugin)

### Tasks 
- Use the `clean` task to remove outputs 
- Use the `build` task to generate schemas and then check compatibility
- Use the `generateSchema` task to just generate schemas
- Use the `testSchemasTask` to check compatibility
- Use the `registerSchemasTask` to register generated schemas  

