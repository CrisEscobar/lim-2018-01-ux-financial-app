# Aplicación financiera "Tus Finanzas"

## 1. Objetivos iniciales del proyecto

El banco más importante del país nos contrató para realizar el rediseño de su nueva aplicación móvil presente en el mercado peruano durante 6 meses, esta aplicación llamada "Tus finanzas" permite a sus usuarios visualizar sus gastos mensuales y fomentar el ahorro. 

Durante la primera semana de entendimiento de los requerimientos, el Product Manager del equipo nos brinda 3 datos importantes:

**a) Tienen claro que el producto es completamente independiente al de su app principal**

>“Todo empezó hace un año cuando vimos que en EEUU y Europa estaban saliendo
  nuevas aplicaciones financieras que nos llamaron la atención. Unas se enfocan
  en darle visibilidad a sus usuarios sobre los gastos, otras en facilitar pagos
  a terceros y otras a fomentar el ahorro. Inspirados en un par de ellas,
  decidimos lanzar una nueva aplicación. Decidimos que era mejor crear un
  producto desde cero - en lugar de modificar la aplicación actual de banca
  móvil - para poder desarrollarla con un equipo totalmente nuevo, en el
  laboratorio de innovación, bajo prácticas ágiles. Sabemos que no es ideal que
  nuestros usuarios tengan que usar dos aplicaciones, pero desarrollar con un
  equipo nuevo que corra ágil nos da mayor libertad.

**b) Realizaron un MVP en iOS en base a los user persona proporcionados por Marketing**

> Empezamos entrevistando a algunos usuarios y revi sando los resultados de un
  estudio de mercado que nos proporcionó el área de marketing. Eso nos dió una
  idea inicial de qué funcionalidades son más relevantes aquí en nuestro
  mercado. Con base en esos resultados, creamos nuestros primeros user personas
  una primaria y una secundaria ( creemos que estas personas no son las que
  nosotros pensábamos inicialmente), y diseñamos y desarrollamos un ‘Producto
  mínimo viable’ (MVP) en 2 meses en iOS. Ese MVP lo hemos lanzado y tenemos
  alrededor de 6 meses de data. Hoy estamos en el proceso de entender los
  resultados iniciales y de sacar una segunda iteración del producto. Y para eso
  las hemos contratado. Toda la documentación de este producto la tenemos en una
  carpeta de [Google Drive](http://bit.ly/uxd-reto-2). Les doy acceso.

**c) Desean tener mayor claridad en el presupuesto a invertir**   
  
> Necesitamos traer una propuesta del nuevo diseño en dos semanas porque tenemos
  que presentarla a nuestro Gerente General en la reunión trimestral. Es
  importante que cualquier cosa que presentemos ya incorpore feedback de testing
  con usuarios. El Gerente General, animado por el crecimiento del número de
  descargas que ha tenido el app, quiere duplicar el presupuesto de Facebook
  Ads… Yo no estoy tan seguro; quisiera que como parte de su trabajo estas
  próximas dos semanas, entendamos ese punto también.”

## 2. Recursos, Herramientas y Proceso

Nos proporcionaron los siguientes recursos:

- Los user persona primario y secundario del proyecto
- Los user flows iniciales y actuales del proyecto del MVP
- El diseño del app en Figma y el Prototipo navegable
- Funnel Analytics de los primeros 6 meses del MVP
- Data de uso del MVP de los primeros 6 meses
- Landing Page inicial del producto

En base a esta información, nosotras destinamos las siguientes [herramientas](https://docs.google.com/spreadsheets/d/182HhpVHB1t0xDIGem7d3zTDdgk0ttrovRzmahXwb3p4/edit?usp=sharing) a implementar y entregables, la cual fue aprobada por el PM.

Con las herramientas seleccionadas y aprobadas, decidimos que el proceso de rediseño para este proyecto sería de la siguiente manera:

<p align = "center"><img src="https://github.com/AilimMoscoso/lim-2018-01-ux-financial-app/blob/master/img/process.png" alt="process" border="0"></p> 

## 3. Entrevista con el cliente

> Puede ver el video de la entrevista [aquí](https://www.useloom.com/share/246e4791e9cc4c4396889131fb7396cf).

> También puede revisar la [guía de entrevista](https://docs.google.com/document/d/1lSs8p5qKMZ9SAjbPPCZ45EkrqxwT7u7SMDUigGlJDP0/edit?usp=sharing).

La entrevista fue realizada el 12 de Setiembre a las 16:30 horas con Gabriela Segura, CEO del banco. Dentro de las conclusiones más relevantes, encontramos:

* La app es un beneficio **sólo para clientes** porque mantienen la info de las cuenta sólo de ellos.
* No descartan la idea de ofrecer información para no clientes, podrían brindar servicios para ellos desde la app, pero no es su objetivo principal.
* El sector a dirigirse es dependiendo del producto: asalariados, emprendedores, es muy variado. Para la app en sí es **gente joven, con economía estable, que ya usan productos tecnológicos en su día a día**. Clase A,B,C actualmente.
* Su **objetivo general** es ofrecer una herramienta que **permita manejar gastos mensuales y ahorrar** ya que es complicado hacerlo con tarjeta, quieren ofrecer esa herramienta como parte de los servicios que ofrece el banco, **es una app independiente a la principal**.
* Su **objetivo secundario** es que sus usuarios tengan controladas sus finanzas.
* Les gusta transmitir que sus usuarios pueden tener la seguridad que sus finanzas están en el lugar correcto, es como un acompañamiento: sueldo, ahorros, préstamos, **quieren ser la entidad que formen parte de sus finanzas en su día a día**.
* Decidieron implementar la app en iOs por el público objetivo A,B ; pero quieren saber si es factible o no, están dispuestos a escuchar más recomendaciones.
* Acerca del presupuesto para otro sistema operativo, no está dentro del actual, pero se puede sustentar si es respaldada con data y pruebas.
* Acerca de promocionar otros productos del banco: consideran mejoras, cambios, pero **no deberían duplicarse con la principal**: crear cuenta, transferir, debe ser complementario.

## 4. Problemas encontrados

### 4.1 Análisis de la data


<p align = "center"><img src="https://github.com/AilimMoscoso/lim-2018-01-ux-financial-app/blob/master/img/data.png" alt="data" border="0"></p>

Lo que principalmente se encontró fue:

* Las visitas del app store bajan un 85% respecto a las del Lading page debido a que la opción está disponible sólo en iOs.
* Los modelos Samsung Galaxy son los más utilizados para entrar a la app, sin embargo tienen el 81% de rebote ya que no pueden terminar la secuencia de descarga.
* Sólo el 2,78% de usuarios entraron al Landing Page través de Facebook.

### 4.2 Testing del MVP

Decidimos testear el producto actual para conocer cómo los usuarios lo perciben y si les es intutitivo seguir las funcionalidades que ofrece la app. Para este fin utilizamos como herramienta **Maze**.

Propusimos que desarrollen las funciones principales a través de tareas y encontramos los siguientes resultados:

<p align = "center"><img src="https://github.com/AilimMoscoso/lim-2018-01-ux-financial-app/blob/master/img/maze.png" alt="maze" border="0"></p>

Puede revisar el detalle del testing del MVP [aquí](https://docs.google.com/document/d/1Clj-jAhcKv1XDAgotBrpzB2Fmlffbi4HYQC_32riPqI/edit?usp=sharing)

## 5. Benchmark

Realizamos una investigación con 4 bancos y 1 app de ahorros, el benchmark nos sirvió para mapear los servicios de la competencia, identificar las buenas y malas prácticas de ellas y poder proponer un mejor producto para nuestro cliente. Puede revisarlo [aquí].(https://docs.google.com/spreadsheets/d/1zwyfHTz9ErV2t1ZiWd_TV9lBQVr_bNDR-iLA9jNY42E/edit?usp=sharing).

## 6. Entrevista a usuarios

> Puede escuchar los audios de las entrevistas [aquí](https://drive.google.com/drive/folders/1YTl9OVkEl4CMr3h6N0Kj8A-K98LQkMyO).

> También puede revisar la [guía de entrevista](https://docs.google.com/document/d/1zkpNdduRrQOyX4_QqJv3oFAbYE0jRZ1fV0Oqh6pJxlA/edit?usp=sharing).

Con los resultados de las entrevistas a 4 usuarios, realizamos un **[Afinity map](https://drive.google.com/open?id=1Zud2AeWdGdeyUXhRERuypYzt67FP3ndX)** para organizar y sintetizar lo que encontramos y así analizar las preferencias o gustos en común que tienen.

## 7. User Persona

Con toda la información proporcionada y la información descubierta en la investigación, decidimos modificar el user persona ya que no reflejaba al usuario objetivo.

<p align = "center"><img src="https://github.com/AilimMoscoso/lim-2018-01-ux-financial-app/blob/master/img/user-persona.png" alt="user-persona" border="0"></p>

## 8. User flow

Respecto al user flow, decidimos que la funcionalidad de "Transacciones" formara parte del menú como una opción complementaria y que no aparezca en el home como una tarea obligatoria a visualizar. Es por esto, que lo definimos de la siguiente manera:

<p align = "center"><img src="https://github.com/AilimMoscoso/lim-2018-01-ux-financial-app/blob/master/img/user-flow.png" alt="user-flow" border="0"></p>

## 9. Recomendaciones a implementar

### 9.1 De las modificaciones

* Como ya se mencionó en el user flow, consideramos que la sección de transacciones debe ser una opción secundaria para que le sirva al usuario como ayuda memoria y no tenga que ingresar a la app principal del banco.
* Respecto al color de la app, se pudo recoger que el color es muy apagado y no motiva a querer registrar información continua, necesitan encontrar una forma dinámica de ingresar e interactuar con todos los beneficios que le ofrece la app. Para fines de este demo, tenemos la propuesta del color lila.

>El color lila en psicología tiene un significado asociado al equilibrio, madurez, empatía y dignidad.

* En cuanto al registro, de acuerdo al resultado del testing debe ser más corto ya que no es una app de extrema seguridad como la principal, no es transaccional, es por esto que el proceso debe ser más directo.
* La información debe estar presentada de forma gráfica en su mayoría para que tengan un registro visual y así sea más fácil y práctico llevar sus cuentas.

### 9.2 De los próximos desarrollos

* Se debería considerar cambiar el nombre de la app "Tus finanzas" ya que no resulta muy amigable para sus usuarios porque según indican es un término muy serio. 

### 9.3 Del presupuesto de marketing

### 10 Prototipo de Alta Fidelidad

Luego de investigar y analizar información nueva y existente, consideramos que la app necesita tener una nueva interface que refleje las verdaderas preferencias de sus usuarios que ya han interactuado con ella, con un aspecto más juvenil y divertido según los datos recogidos en las entrevistas. A continuación presentamos nuestro [prototipo de alta fidelidad]().


## 11. Diseño para desarrolladores
## 12. Video Demo

























