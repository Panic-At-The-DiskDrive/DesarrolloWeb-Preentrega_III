# Desarrollo Web - Preentrega 3

## Para poner en práctica todos los conocimientos adquiridos, te proponemos que el proyecto completo se pueda visualizar de manera correcta en dispositivos mobile y desktop. El mismo deberá estar configurado y con código SASS aplicado.

### Cómo arrancar el proyecto

1. **Clonar el repositorio**  
   ```bash
   git clone https://github.com/Panic-At-The-DiskDrive/DesarrolloWeb-Preentrega_III.git
   ```

2. **Entrar a la carpeta del proyecto**  
   ```bash
   cd DesarrolloWeb-Preentrega_III
   ```

3. **Instalar dependencias**  
   ```bash
   npm install
   ```

4. **Iniciar el servidor de desarrollo**  
   ```bash
   npm start
   ```

## Objetivos
+ Realizar la estructura final de la web.

+ Efectuar el estilo final de la web.

+ Realizar una correcta implementación de SASS.

## Se debe entregar
+ Estructura del HTML avanzada

+ Archivo CSS, Archivos SCSS

+ Git y GitHub para brindar acceso al proyecto versionado

### Criterios de evaluación
+ Estructura final de la web (HTML) - Estilo, funcionalidad y contenido Estilo: Se observa un uso de nombres de clases correcto, sin caer en clases redundantes o irrelevantes. Linkea correctamente a el/los archivos de CSS que son generados por el SCSS. Funcionalidad: Las páginas tienen enlaces funcionales. Las imágenes están bien cargadas y resultan pertinentes. Las rutas relativas son correctas. Contenido: la información está correctamente estructurada, usando los tags correctos para cada tipo de contenido, ya sean tablas, listas, titulares, párrafos o imágenes. El contenido se distribuye de forma no monótona y tiene varios niveles de lectura. Las imágenes tienen un tamaño apropiado al que ocupan en el contenido.

+ Estructura final de la web (HTML) - Prolijidad del código y tags Prolijidad del código: Presenta tabulaciones correctas y ordenadas, denotando jerarquía entre los elementos? ¿Hay consistencia entre la estructura HTML de diferentes páginas? Tags: El nesting es óptimo, usando la menor cantidad de tags posibles. Se observa un uso de tags semánticos correcto y estructuración de la página desde el HTML El alt de las imágenes es pertinente y descriptivo?

+ Estilo final de la web (CSS) - Estilo del diseño web Estilo del diseño web: Las transiciones y animaciones son apropiadas, y se usan con elementos que merecen la atención del usuario. Hay una paleta de colores con contrastes pertinentes y se respeta a lo largo de las páginas del sitio web. El texto es legible.

+ Estilo final de la web (CSS y SCSS/SASS) - Código y diseño de la estructura visual Código de la estructura visual o layout: ¿Utiliza flex y grid pertinente al tipo de layout a generar? Evita forzar flex o grid para elementos que no lo necesitan y se resuelven con box-modelling. Diseño de la estructura visual o layout: ¿El diseño del layout es consistente página a página, planteando una navegación intuitiva y navegable? Los elementos de la misma jerarquía y los estilos definidos para los elementos se mantienen consistentes a lo largo de las páginas.

+ Estilo final de la web (SCSS/SASS) - Utilización de frameworks Utilización de frameworks: Utiliza el framework para maquetar y no para traerse solamente componentes (carousel, menú hamb, modal, etc).

+ Estilo final de la web (CSS y SCSS/SASS) - Entendimiento Entendimiento del CSS: ¿Expande sobre elementos que ya había creado con clases que los modifican? ¿Genera estilos que son fáciles de cambiar o transformar para diferentes tamaños de dispositivo? Entendimiento de SCSS/SASS: ¿Crea mixins y evita repetir código que usa a lo largo de su web? Utiliza operadores como each para armar clases de forma dinámica. Utiliza variables para no tener que repetir valores innecesarios.

+ Estilo final de la web (CSS y SCSS/SASS) - prolijidad del código y media queries Media queries & Responsive: Usa unidades relativas. El sitio web cuenta con una buena navegación en numerosos tamaños, en particular en mobile, laptop y desktop. Prolijidad del código: Usa tabulaciones y nesting bien estructurado en el SCSS. Usa & para realizar selectores óptimos con pocas repeticiones.

---

## Tecnologías utilizadas

- **HTML5** semántico  
- **CSS3** con **SASS** (`@use` / `@forward`)  
- **Bootstrap 5.3** para maquetación responsive  
- **live-server** (vía `npm start`) para desarrollo local  

---