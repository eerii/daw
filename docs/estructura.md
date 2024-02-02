# Estructura de arquivos

![Estructura de arquivos](./estructura.png)

- `index.html`: Páxina base da web (dirección /)
- `paxina*.html`: Outras páxinas, por exemplo, formulario de contacto ou lista de sesións
- `blog/`: Contén os artículos do blog da web
- `components/`: Pequenos arquivos html que poden ser reutilizados en múltiples páxinas
- `assets/`: Arquivos externos ó hipertexto
    - `media/`: Todo o contido multimedia necesario para a aplicación
        - `images/`: Imaxes (pode ter subcarpetas para unha mellor organización)
        - `fonts/`: Tipografías
    - `style/`: Follas de estilo css
        - `reset.css`: Un estilo homoxeneo de css para tódolos navegadores con valores por defecto razoables
        - `base.css`: Estilo global para cada selector (p, h1, img...)
        - `classes.css`: Clases particulares con estilo propio (tarxetas, diapositivas...)
    - `lib/`: Scripts para funcionalidade interactiva con javascript
- `docs/`: Todos os arquivos de documentación e planificación (non pertencentes á web)
