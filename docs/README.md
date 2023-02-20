# PDF Reader

El componente _PDF Reader_ permite una lectura rápida de archivos PDF dentro de la tienda.

![Media Placeholder](/assets/img/pdf-reader.PNG)

## Configuración

### Paso 1 - Agregar el componente a las dependencias de su aplicación

Dentro del archivo `manifest.json` de su aplicación, debe agregar la siguiente dependencia: 

```json
"dependencies": {
  ...
  "itgloberspartnercl.pdf-reader": "0.x"
  ...
}
```

### Paso 2 - Declarar el bloque principal en su aplicación

Agregue el bloque `pdf-reader` donde requiera utilizarlo dentro de su aplicación. Por ejemplo: 

```json
{
  ...
  "pdf-reader": {
    "props": {
      ...
      "pdfUrl": "assets/documents/Sample_PDF.pdf",
      "width": 500,
      "height": 500,
      "blockClass": "pdf__reader"
      ...
    }
  }
}
```

| Nombre de la propiedad | Tipo | Descripción | Valor por defecto |
| -- | -- | -- | -- |
| `pdfUrl` | `String` | Url del PDF | "" |
| `width` | `Number` | Ancho del componente |  |
| `height` | `Number` | Alto del componente |  |

## Customización

Para aplicar personalizaciones de CSS en este y otros bloques, siga la guía [Uso de identificadores de CSS para la personalización de la tienda](https://developers.vtex.com/docs/guides/vtex-io-documentation-using-css-handles-for-store-customization).


| CSS HANDLES |
| -- |
| `pdf__contenedor` |

## Colaboradores

- **Alan Agustín Huismann**