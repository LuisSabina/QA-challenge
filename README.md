# QA-challenge
A modo de resumen se deja este readme:
Punto 3: El punto 1 y punto 2 están hechos en excel y en postman, el punto 3 lo describiré en este readme. Para hacer el punto 1 usé un excel para los casos de prueba básicos sobre las funcionalidades de la api de temperatura, lo encuentro práctico, se puede colaborar con colegas si se usa google sheets. Son casos de prueba funcionales sobre el contrato de la api, para probar lo que dice que hace, si realmente lo hace. 
Para hacer el punto 2, también use un excel para los casos de prueba, esta vez hice algunas pruebas funcionales básicas sobre el contrato de la api, según la documentación y además hice algunos casos de prueba específicos inventados cuyos test son más complejos y que podrían llegar a requerirse en una api productiva. 
Para finalizar, creo que los puntos a tener en cuenta para probar una API, son: Probar lo antes posible para lograr solucionar los bugs con anticipación, sobre cada microservicio que se va desarrollando. De esta manera, se va conociendo cada parte del sistema, su funcionamiento y la interacción entre microservicios. Si se ha probado cada parte del sistema por separado, es más fácil encontrar errores y sus soluciones, probando de esta forma modular. Y además no arrastrar un funcionamiento defectuoso a etapas avanzadas del proyecto donde se pueden producir demoras en las entregas. 
Al probar una API lo primero que se tendría que revisar es la parte funcional, pedir la documentación y de acuerdo a las especificaciones diseñar casos de prueba para probar cada una de las funciones y comprobar que responde adecuadamente. 
Luego se probaría la seguridad, comprobar la autenticación, es decir que sólo tenga acceso al servicio el usuario que tenga permiso para ello. 
También debería probarse que si hay datos sensibles, estén encriptados. Posteriormente se podrían hacer pruebas de rendimiento con JMeter y luego se podrían hacer pruebas de integración con otras apis, hacer funcionalidades completas que involucren varios microservicios.

Dejo los archivos json de la collection de postman y el excel con los casos de prueba y un documento word con una explicación más detallada del punto 3 .
Espero sea de su agrado. 
Saluda Atte, Luis Sabina
