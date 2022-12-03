# test

```
<meta name="viewport" content="width=[Pixeles del mínimo ancho para visualizar bien la web]" />
```

## RDFa Resource Descriptive Framework in Attributes

```
about: sirve para especificar la fuente de los metadatos
content: anula el contenido del elemento cuando usa el atributo de propiedad
datatype: especifica el tipo de dato de texto que quiere usar con el atributo adecuado
rel y rev: especifica la relación directa e inversa con otra fuente
src, href y resource: en este caso, este atributo especifica un recurso asociado
typeof: se usa para ordenar elementos en una categoría, por ejemplo
```

## Microdatos

```
itemid: se usa para indicar un identificador único del elemento
itemprop: indica que la etiqueta tiene el valor de una propiedad concreta del elemento. Por ejemplo, itemprop=”name”
itemref: este atributo se utiliza para referencias de propiedades de un elemento que no estén en la etiqueta itemscope. De esta manera, está proporcionando un listado de ids de elementos con más propiedades que en otra parte del documento
itemsope: crea el elemento y, además, indica que el resto contiene información relacionada
itemtype: describe el elemento junto a sus propiedades con una URL válida de un vocabulario
```

## JSON-LD Javascript Object Notation for Linked Objects

```
<script type="aplication/ld+json">
{
  "@context": "http://schema.org",
  "@type": "Restaurant",
  "address": {
    "@type": "PostalAddress",
    "addressLocality": "Cuauhtémoc",
    "addressRegion": "Ciudad de México",
    "postalCode": "123456",
    "streetAddress": "222 Paseo de la reforma",
    },
    "name": "RestaurantePepeYToño",
    "openingHours": [
      "Mo-Fr 11:00-18:00"
    ],
    "telephone": "(123) 456-7890",
    "url": "http://url.com",
    "logo": "http://url.com/images/logo.png",
    "sameAs": ["http://facebook.com/restaurantepyt",
      "http://twiter.com/restaurantepyt",
      "http://plus.google.com/+restaurantepyt"
    ]
}
</script>
```

Semantic inspector / chrome extension
https://search.google.com/test/rich-results / resource to valid structure data

last line added
otro
merged