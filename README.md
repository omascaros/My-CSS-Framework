# Framework css

Framework CSS realizado con propósitos didácticos. Para practicar los conocimientos
de CSS y SASS.

### Estructura de archivos

--scss
		style.scss

        --base
             _reset.scss
             _fuentes.scss
             _links.scss      
             _elementos.scss
             _tipografia.scss
             _formularios.scss

		--componentes
             _navegacion.scss
             _botones.scss
             _tablas.scss
                    
        --layout
			_sitio.scss

        --lib
			_mixins.scss
			_flex.scss
			_placeholders.scss
			_variables.scss

### Cómo funciona

#### style.scss
Por temas de optimización, y para que no se añada mas CSS del estrictamente necesario,
en el archivo scss/style.scss hay que comentar las líneas de código que no queremos que sea compilado.

#### variables.scss
En el archivo scss/lib/_variables.scss se encuentran las variables que ayudan a configurar
el aspecto de nuestro site, donde podemos elegir colores, fuentes, tamaños...