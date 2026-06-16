# Proyecto de Prueba para aprender

Este proyecto es para practicar la construccion de archivos en diferentes formatos, a saber: markdown, json, yaml, toon

## Navegacion basica: 

Menu: Franja superior

Paginas:
- Home
- Acerca de
- Lista de comandos

Footer:
- Contacto
- Telefonos

## Stack:
1. html
2. tailwind 
3. Sin CSS
4. variables .env
5. javascript
6. React y Next.js

## Diseno:
- Tipo SAP tanto en web como en movil Ver: (https://www.sap.com/latinamerica/about/company.html)
- Responsivo
- Menu hamburguesa para movil
- Usar todo el ancho de la pagina

## Recomendaciones:
- Markwdown para textos explicativos
- json para definir estructuras de entrada o de salida de datos
- YAML para describir configuraciones 
- Toon es mas bien para tablas explicativas 


> ***Priorizar siempre el ahorro de tokens***

## Documentacion:

Para informacion adicional use:

**Para Markdown**
>>https://www.markdownguide.org/basic-syntax/

**Para JSON**
>https://developer.mozilla.org/es/docs/Learn_web_development/Core/Scripting/JSON

**Para YAML**
>https://yaml.org/

## Ejemplos:

Ejemplo de un codigo JSON

```JSON
const incidentData =
{
    "incidente_id": "INC006",
    "metadatos_estructurados": {
        "modulo": "FI-AP",
        "tipo_causa_raiz": "Falla de Interfaz / Sistema",
        "fecha_apertura": "2026-02-06 17:49:58",
        "impacto": "3 - Bajo",
        "area_proceso_escenario": ["SAP S/4HANA AP", "Interfaz SAP a SWIFT", "Liberación de pagos"],
        "resumen_problema_usuario": "Se solicita verificar liberación de pagos dado que los mismos no aparecen en SWIFT",
        "resumen_solucion_usuario": "Se identificó que el problema se debía a un inconveniente en la salida del sistema, ya que los archivos dejaron de llegar a la interfaz temporalmente. Se restableció el flujo de información, logrando que los archivos pasaran a la interfaz y los pagos fueran procesados de manera satisfactoria sin intervención adicional. Tipología: Falla de Interfaz / Sistema"
    }
}
```
## Versiones de este documento:

```YAML
- Documento original: Enero 2026
- 1ra Revision: Junio 2026
```

