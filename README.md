# Torneo UFC en Base de Datos NoSQL
Base de datos creada en MongoDb, creada con en el propósito de organizar por colecciones los actores y eventos necesarios que se deben registrar en un torneo de UFC.

# Creación de BD y tabla de referis - MongoDB Shell
1. use torneo_ufc
2. db.referis.insert({{"_id": 1, "nombres": "Test Nombre", "apellidos": "Test Apellido", "telefono": "xxxxxxx", "pais": "EE.UU", "estado": "Alabama" }})
3. show dbs

# Consultas Básicas
db.getCollection('combates').find({});
db.getCollection('jueces').find({});
db.getCollection('luchadores').find({});
db.getCollection('programaciones').find({});
db.getCollection('referis').find({});
