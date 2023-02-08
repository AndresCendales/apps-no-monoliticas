# Grupo Krusty Brand


# Entrega 1

### Estructura del proyecto
.\
└── entrega_1 \
....├── ShippingDomain.cml\
....├── DeliveryDomain.cml \
....├── delivery_context.png \
....└── shipping_context.png 


### Dominios y Subdominios

Se identifican dos dominios principales Shipping y Delivery los cuales resuelven las necesidades de negocio de mensajeria y domicilio de comida respectivamente. En la carpeta entrega1 se encuentra 1 archivo .cml que sigue la sintaxix de [context mapper](https://contextmapper.org/) con los detalles de cada caso. 

Debido a que son dominios con muchas similitudes se reuso varios de los subdominos de soporte o genericos.

Adicionalmente se identifica al menos un BoundedContext por cada subdominio definido, en las imagenes entrega1/delivery_context.png y entrega1/shipping_context.png muestran la representacion grafica de cada uno de los dominios de delivery y shipping respectivamente