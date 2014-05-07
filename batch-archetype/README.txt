In archetype directory:

mvn clean install
mvn install archetype:update-local-catalog

In workspace directory:
mvn archetype:generate -DarchetypeCatalog=local

then select batch-archetype options 