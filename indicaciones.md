# PROFE ADMIN — Documento de construcción de página web para OpenCode

## INSTRUCCIÓN PRINCIPAL

Construye una página web profesional, moderna, responsive y funcional para la marca **PROFE ADMIN**.

No quiero solamente un mockup. Quiero que conviertas esta especificación directamente en una página web funcional, separando correctamente los archivos, manteniendo una estructura limpia y fácil de modificar.

La página debe estar preparada para ejecutarse en **localhost con XAMPP**.

Si el proyecto ya contiene archivos, analízalos primero y reutiliza lo que sea útil sin destruir información existente. Si no existe una estructura adecuada, créala.

---

# 1. OBJETIVO DEL SITIO

Profe Admin es una marca enfocada en educación, administración, consultoría, herramientas administrativas y soluciones para personas y empresas.

La página debe servir como sitio principal para:

- Mostrar los servicios.
- Explicar qué hace Profe Admin.
- Captar estudiantes, profesionales, emprendedores y empresas.
- Permitir que los visitantes contacten directamente por WhatsApp Business.
- Presentar los servicios de manera profesional.
- Preparar la estructura para agregar posteriormente nuevos servicios, productos, cursos, plantillas y sistemas.

El objetivo comercial principal es conseguir contactos.

El CTA principal de toda la página debe ser:

**Contactar por WhatsApp**

Número:

**+57 318 033 52 55**

WhatsApp Business:

**https://wa.me/573180335255**

---

# 2. TECNOLOGÍA

Construye la página utilizando una arquitectura sencilla y mantenible.

Preferencia tecnológica:

- PHP
- HTML5
- CSS3
- JavaScript
- Bootstrap o CSS propio si resulta más apropiado
- Font Awesome o una librería de iconos equivalente
- No utilizar frameworks innecesariamente complejos.

Debe funcionar correctamente en:

**XAMPP + Apache + PHP**

No utilizar base de datos para esta primera versión.

La página debe poder ejecutarse colocando el proyecto dentro de:

`htdocs/profe-admin/`

Y entrando posteriormente a:

`http://localhost/profe-admin/`

---

# 3. ESTRUCTURA DE ARCHIVOS

No concentres todo en un único archivo.

Crea una estructura organizada similar a:

```text
profe-admin/
│
├── index.php
│
├── assets/
│   ├── css/
│   │   └── style.css
│   │
│   ├── js/
│   │   └── script.js
│   │
│   └── img/
│
├── includes/
│   ├── header.php
│   ├── navbar.php
│   └── footer.php
│
└── README.md
```

Si consideras que otra estructura es mejor, puedes mejorarla, pero mantén separación clara entre:

- estructura
- estilos
- JavaScript
- componentes reutilizables
- imágenes

---

# 4. IDENTIDAD VISUAL

La marca debe sentirse:

- Moderna
- Profesional
- Cercana
- Educativa
- Tecnológica
- Dinámica
- Humana
- Innovadora

Evita una apariencia corporativa antigua o excesivamente formal.

NO utilizar como concepto visual principal:

- Trajes ejecutivos genéricos.
- Edificios corporativos.
- Maletines.
- Gráficos financieros genéricos.
- Diseños grises y aburridos.
- Exceso de azul corporativo tradicional.

Utilizar:

- Fondos claros.
- Colores vivos pero profesionales.
- Gradientes sutiles.
- Tarjetas con bordes redondeados.
- Sombras suaves.
- Iconografía moderna.
- Espacios amplios.
- Tipografía moderna.
- Buena jerarquía visual.

La interfaz debe parecer una mezcla entre:

**plataforma educativa + consultoría moderna + startup tecnológica.**

---

# 5. NAVBAR

Crear una barra de navegación profesional y responsive.

Logo/texto:

**PROFE ADMIN**

Menú:

- Inicio
- Servicios
- Soluciones
- Sobre Profe Admin
- Contacto

Agregar botón destacado:

**WhatsApp**

El navbar debe:

- Permanecer visible al hacer scroll.
- Tener efecto visual al hacer scroll.
- Convertirse en menú hamburguesa en móvil.
- Ser completamente responsive.

---

# 6. HERO

Crear una sección principal visualmente fuerte.

Título:

**Administración que se aprende, se aplica y transforma.**

Subtítulo:

**Clases, asesorías, conferencias, herramientas y soluciones administrativas para estudiantes, profesionales, emprendedores y empresas.**

Botones:

**Ver servicios**

**Hablar por WhatsApp**

Mostrar:

**WhatsApp Business: +57 318 033 52 55**

El hero debe transmitir inmediatamente:

Educación + Administración + Tecnología + Soluciones.

Crear elementos visuales modernos relacionados con:

- aprendizaje
- administración
- tecnología
- gestión
- personas
- herramientas digitales

No sobrecargar el hero.

---

# 7. SECCIÓN: ¿QUÉ PUEDO HACER POR TI?

Título:

**Soluciones para aprender, mejorar y gestionar**

Texto:

**Desde una clase personalizada hasta el desarrollo de herramientas administrativas para una empresa, Profe Admin combina conocimiento administrativo, formación práctica y tecnología para resolver necesidades reales.**

Crear cinco tarjetas:

### Estudiantes
Apoyo académico, clases, monitorías y acompañamiento.

### Profesionales
Asesorías, capacitación, herramientas y desarrollo profesional.

### Emprendedores
Herramientas y soluciones para organizar y gestionar negocios.

### Empresas
Capacitación, auditorías, procesos y soluciones administrativas.

### Equipos de trabajo
Formación, desarrollo y acompañamiento para mejorar la gestión.

---

# 8. SERVICIOS

Título:

**Mis servicios**

Subtítulo:

**Conocimiento, herramientas y soluciones para diferentes necesidades administrativas.**

Crear 9 tarjetas.

## 01 — CLASES

Clases personalizadas de administración, gestión, recursos humanos, finanzas, marketing, estrategia y otras áreas relacionadas.

Icono sugerido: graduación/libro.

CTA:

**Solicitar información**

---

## 02 — ASESORÍAS

Acompañamiento personalizado para resolver dudas, proyectos, trabajos académicos y situaciones administrativas.

Icono sugerido: comentarios/asesoría.

CTA:

**Solicitar información**

---

## 03 — CONFERENCIAS

Conferencias y charlas sobre administración, gestión empresarial, recursos humanos, liderazgo, productividad y organizaciones.

Icono sugerido: micrófono/presentación.

CTA:

**Solicitar información**

---

## 04 — SISTEMAS DE ADMINISTRACIÓN

Diseño y desarrollo de sistemas y soluciones digitales para gestionar procesos administrativos y empresariales.

Icono sugerido: monitor/software.

CTA:

**Solicitar información**

---

## 05 — HERRAMIENTAS DE ADMINISTRACIÓN

Diseño de herramientas prácticas para mejorar procesos, controlar información, analizar datos y facilitar la gestión.

Icono sugerido: herramientas/dashboard.

CTA:

**Solicitar información**

---

## 06 — PLANTILLAS DE ADMINISTRACIÓN

Plantillas profesionales para Excel, gestión administrativa, recursos humanos, planeación, finanzas, procesos y organización empresarial.

Icono sugerido: hoja/documento.

CTA:

**Solicitar información**

---

## 07 — AUDITORÍAS

Revisión y análisis de procesos, documentos, información y procedimientos administrativos para identificar oportunidades de mejora.

Icono sugerido: lupa/checklist.

CTA:

**Solicitar información**

---

## 08 — CAPACITACIONES PARA EMPRESAS

Capacitaciones personalizadas para empresas y equipos de trabajo de acuerdo con sus necesidades.

Icono sugerido: presentación/equipo.

CTA:

**Solicitar información**

---

## 09 — MONITORÍAS

Acompañamiento académico y práctico para estudiantes y personas que necesitan apoyo durante sus procesos de aprendizaje.

Icono sugerido: estudiante/tutor.

CTA:

**Solicitar información**

---

# 9. BOTONES DE SERVICIO

Todos los botones:

**Solicitar información**

deben abrir WhatsApp utilizando:

`https://wa.me/573180335255`

Preferiblemente incluir un mensaje precargado diferente según el servicio.

Ejemplo:

`https://wa.me/573180335255?text=Hola%20Profe%20Admin%2C%20estoy%20interesado%20en%20las%20clases.`

Crear mensajes adecuados para cada servicio.

---

# 10. SOLUCIONES PARA EMPRESAS

Crear una sección visual diferenciada.

Título:

**También trabajo con empresas**

Texto:

**Diseño soluciones adaptadas a las necesidades reales de cada organización.**

Mostrar las siguientes categorías:

- Recursos Humanos
- Administración
- Procesos
- Planeación
- Herramientas digitales
- Capacitación
- Análisis empresarial
- Gestión de información

Agregar CTA:

**Quiero una solución para mi empresa**

El botón debe abrir WhatsApp.

---

# 11. POR QUÉ PROFE ADMIN

Título:

**¿Por qué Profe Admin?**

Crear cinco bloques:

### Enfoque práctico
Aprende y aplica los conceptos a situaciones reales.

### Soluciones personalizadas
Cada servicio se adapta a la necesidad del cliente.

### Administración + tecnología
Combinar conocimientos administrativos con herramientas digitales.

### Acompañamiento cercano
Comunicación clara y acompañamiento durante el proceso.

### Para personas y empresas
Servicios dirigidos tanto a estudiantes como a organizaciones.

---

# 12. PROCESO DE TRABAJO

Título:

**¿Cómo trabajamos?**

Crear un proceso visual de cuatro pasos.

### 01
**Cuéntame tu necesidad**

El cliente explica qué necesita.

### 02
**Analizamos tu situación**

Identificamos el problema, objetivo o necesidad.

### 03
**Diseñamos la solución**

Definimos el servicio y la forma de trabajo.

### 04
**Trabajamos juntos**

Ejecutamos el servicio y damos acompañamiento.

---

# 13. SOBRE PROFE ADMIN

Crear una sección llamada:

**Sobre Profe Admin**

Texto base:

**Profe Admin es un espacio dedicado a la educación, la administración y el desarrollo de soluciones prácticas para personas y organizaciones.**

**La propuesta combina formación, conocimiento administrativo, tecnología y acompañamiento para convertir conceptos en herramientas que puedan aplicarse en situaciones reales.**

No inventar títulos académicos, empresas, certificaciones, años de experiencia o información personal que no haya sido proporcionada.

Crear una composición visual moderna para esta sección.

---

# 14. CTA FINAL

Crear una sección destacada.

Título:

**¿Necesitas aprender, mejorar o solucionar algo relacionado con la administración?**

Texto:

**Cuéntame qué necesitas y encontremos juntos la mejor solución.**

Botón:

**Contactar por WhatsApp**

Número:

**+57 318 033 52 55**

Agregar una indicación:

**WhatsApp Business**

---

# 15. FOOTER

Crear footer profesional.

Mostrar:

**PROFE ADMIN**

**Administración, educación y soluciones para personas y empresas.**

Enlaces:

- Inicio
- Servicios
- Soluciones
- Sobre Profe Admin
- Contacto

Contacto:

**WhatsApp Business**
**+57 318 033 52 55**

Botón:

**Escribir por WhatsApp**

Agregar espacios preparados para redes sociales, sin inventar URLs de redes sociales.

---

# 16. RESPONSIVE

La página debe funcionar correctamente en:

- Desktop
- Laptop
- Tablet
- Smartphone

En móvil:

- Navbar hamburguesa.
- Tarjetas en una sola columna.
- Botones fáciles de pulsar.
- Texto correctamente escalado.
- No debe existir scroll horizontal.
- El WhatsApp debe ser especialmente visible.

---

# 17. UX Y CONVERSIÓN

La prioridad es convertir visitantes en contactos.

Usar llamados a la acción de WhatsApp estratégicamente:

1. Navbar.
2. Hero.
3. Cada servicio.
4. Sección empresarial.
5. CTA final.
6. Footer.

Agregar, si resulta apropiado, un botón flotante de WhatsApp en la esquina inferior derecha.

El botón flotante debe:

- Ser visible pero no invasivo.
- Tener icono de WhatsApp.
- Mostrar tooltip o texto "¿Hablamos?"
- Abrir directamente el WhatsApp Business.

---

# 18. ANIMACIONES

Utilizar animaciones sutiles:

- Fade-in al aparecer secciones.
- Hover en tarjetas.
- Elevación suave de tarjetas.
- Transiciones de botones.
- Scroll suave entre secciones.

No utilizar animaciones exageradas.

La página debe cargar rápido.

---

# 19. SEO BÁSICO

Agregar:

Title:

**Profe Admin | Administración, asesorías, clases y soluciones empresariales**

Meta description:

**Profe Admin ofrece clases, asesorías, conferencias, capacitaciones, auditorías, herramientas, plantillas y soluciones administrativas para estudiantes, profesionales, emprendedores y empresas.**

Utilizar correctamente:

- H1
- H2
- H3
- alt en imágenes
- estructura semántica HTML5

---

# 20. ACCESIBILIDAD

Implementar:

- Contraste adecuado.
- Textos legibles.
- Estados hover y focus.
- Navegación mediante teclado.
- Etiquetas aria cuando sean necesarias.
- Botones y enlaces claramente identificables.
- Alt descriptivo para imágenes.

---

# 21. CÓDIGO

El código debe ser:

- Limpio.
- Modular.
- Comentado únicamente cuando sea necesario.
- Fácil de mantener.
- Sin código duplicado innecesario.
- Responsive.
- Seguro para una página pública básica.

No introducir dependencias innecesarias.

No crear una base de datos en esta primera versión.

No crear un sistema de login.

No crear un panel administrativo todavía.

---

# 22. DATOS QUE NO DEBES INVENTAR

No inventes:

- Dirección.
- Correo electrónico.
- Redes sociales.
- Precios.
- Testimonios.
- Número de clientes.
- Años de experiencia.
- Certificaciones.
- Empresas atendidas.
- Estadísticas.
- Títulos académicos.

Si una sección normalmente necesitaría estos datos, utiliza un espacio preparado para agregarlos posteriormente.

---

# 23. IMÁGENES

Si no existen imágenes reales de Profe Admin, utiliza recursos visuales genéricos o ilustraciones coherentes.

No inventar fotografías personales del propietario.

Crear una carpeta:

`assets/img/`

para futuras imágenes.

Utilizar nombres descriptivos para los archivos.

---

# 24. FUNCIONALIDAD

Verificar que funcionen:

- Navegación del menú.
- Scroll a secciones.
- Botones.
- WhatsApp.
- Menú móvil.
- Animaciones.
- Responsive.
- Footer.
- Todos los enlaces internos.

Todos los botones de contacto deben terminar en:

`https://wa.me/573180335255`

---

# 25. CALIDAD FINAL

Antes de terminar:

1. Revisar todo el código.
2. Verificar errores PHP.
3. Verificar errores JavaScript.
4. Verificar rutas CSS.
5. Verificar rutas JS.
6. Verificar navegación.
7. Verificar responsive.
8. Verificar WhatsApp.
9. Verificar que no haya texto de ejemplo como "Lorem ipsum".
10. Verificar que no haya contenido inventado.
11. Verificar que todos los servicios aparezcan.
12. Verificar que el número de WhatsApp sea exactamente:

**+57 318 033 52 55**

13. Verificar que el enlace sea:

**https://wa.me/573180335255**

---

# 26. RESULTADO ESPERADO

Al finalizar quiero tener una página web completa y funcional de **PROFE ADMIN**, no solamente un diseño.

Debe sentirse como una marca profesional de:

**Educación + Administración + Tecnología + Consultoría.**

La página debe estar orientada a generar contactos y presentar claramente los siguientes servicios:

- Clases
- Asesorías
- Conferencias
- Sistemas de administración
- Herramientas de administración
- Plantillas de administración
- Auditorías
- Capacitaciones para empresas
- Monitorías

El resultado debe ser suficientemente profesional para utilizarlo como página web oficial de Profe Admin.

---

# INSTRUCCIÓN FINAL PARA OPENCODE

Primero analiza el directorio actual del proyecto.

Si ya existe código, no lo sobrescribas sin analizarlo.

Después crea o reorganiza los archivos necesarios y construye la página completa.

Cuando termines:

1. Comprueba que todos los archivos existan.
2. Comprueba que PHP no tenga errores de sintaxis.
3. Comprueba que los enlaces internos funcionen.
4. Comprueba que WhatsApp funcione.
5. Comprueba la versión responsive.
6. Explica brevemente qué archivos creaste o modificaste.
7. Indica cómo ejecutar el proyecto en XAMPP.
8. No te limites a describir lo que habría que hacer: **haz los cambios directamente en el proyecto.**
