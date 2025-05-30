# 📦 UCSE Box Model y Posicionamiento CSS

¡Bienvenido/a al repositorio de prácticas sobre el **Box Model** y **posicionamiento en CSS**! 🚀

Este proyecto contiene ejemplos prácticos y código para comprender cómo funcionan los elementos en la web, cómo se distribuyen en la página y cómo podemos manipular su apariencia y ubicación usando CSS.

---

## 📚 Teoría: Box Model en CSS

El **Box Model** es el modelo de caja que utiliza CSS para representar y diseñar los elementos HTML. Cada elemento se representa como una caja rectangular que está compuesta por:

- **Contenido (content):** Es el área donde se muestra el texto o las imágenes.
- **Relleno (padding):** Espacio entre el contenido y el borde de la caja.
- **Borde (border):** El contorno que rodea el padding (relleno) y el contenido.
- **Margen (margin):** Espacio exterior que separa la caja de otros elementos.

```
+---------------------------+
|        margin             |
|  +---------------------+  |
|  |      border         |  |
|  |  +---------------+  |  |
|  |  |   padding     |  |  |
|  |  | +-----------+ |  |  |
|  |  | | content   | |  |  |
|  |  | +-----------+ |  |  |
|  |  +---------------+  |  |
|  +---------------------+  |
+---------------------------+
```

### Propiedades principales:
- `width` y `height`: definen el tamaño del contenido.
- `padding`: espacio interno.
- `border`: borde de la caja.
- `margin`: espacio externo.

---

## 📐 Posicionamiento en CSS

El posicionamiento permite controlar cómo y dónde se muestran los elementos en la página. Las propiedades más importantes son:

- **static:** Valor por defecto. El elemento sigue el flujo normal del documento.
- **relative:** Se posiciona relativo a su posición original.
- **absolute:** Se posiciona respecto al ancestro posicionado más cercano (que no sea static).
- **fixed:** Se posiciona respecto a la ventana del navegador.
- **sticky:** Se comporta como relative hasta que se alcanza un punto, luego como fixed.

### Ejemplo de uso en este repositorio:
- `.container` usa `position: relative;` para que los elementos hijos con `position: absolute;` se posicionen respecto a él.
- `.bi-heart-fill` y `.icono-whatsapp` usan `position: absolute;` para ubicarse en lugares específicos dentro de su contenedor.

---

## 📝 Estructura del repositorio
- `index.html`: Estructura básica de la página y ejemplos de elementos.
- `css/styles.css`: Estilos que demuestran el uso del box model y posicionamiento.

---

## 👨‍💻 Autor
Este repositorio fue creado con fines educativos para la materia **Programación 2** en UCSE.

¡Explora, prueba y aprende! ✨
