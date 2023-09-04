![Logo UPC](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)

Universidad Peruana de Ciencias Aplicadas

Ingeniería de Software

Ciclo 2023-02

# Aplicaciones Web

Sección WS52

**Profesor:** Juan Carlos Tinoco Licas

***INFORME DE TRABAJO FINAL - TB1***

**Startup:** StudiStay Connect

**Producto:** StudiStay

**Integrantes:**

- Checa Apolinario, Paolo Sebastián
- Yance Gutierrez, Franco Felix
- Ortega Vélez, Jamutaq Piero

Link al video de exposición: [Youtube]()

Agosto del 2023

---
# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de la modificación |
| - | - | - | - |
|  |  |  |  |
|  |  |  |  |

---
# Project Report Collaboration Insights

Link de repositorio Github: 

---
# Contenido 
## Tabla de contenidos


---
# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

ABET – EAC - Student Outcome 5

Criterio: Trabaja efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo; crea un entorno colaborativo e inclusivo y establece metas, planifica tareas y cumple objetivos.

En el siguiente cuadro se describe las acciones realizadas y enunciados de 
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro 
del ABET – EAC - Student Outcome 5.

| Criterio específico | Acciones realizadas | Conclusiones |
| - | - | - |
| Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software. | | |
| Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software. | | |

---
# Capítulo I: Introducción

## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
#### 1.2.2.2. Lean UX Assumptions.
#### 1.2.2.3. Lean UX Hypothesis Statements.
#### 1.2.2.4. Lean UX Canvas.

### 1.3. Segmentos objetivo.

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores

| Nombre del Competidor | Descripción |
|:----|:----:|
| Roomate Lima (Web browser) https://www.roommates.pe | 1. Permite encontrar un roommate adecuado, publicando la habitación que deseas alquilar o también buscando un lugar perfecto para vivir. 2. Analiza tus posibilidades para que puedas reunirte con ellos y de esta forma sepas si son los roommates que estás buscando. |
| Urbania (Web browser) https://urbania.pe | 1. Plataforma en la que las inmobiliarias y dueños directos de todo el país para ofrecer las mejores opciones de inmuebles. 2. Accede de forma fácil y segura a los avisos contactados, favoritos, las notas que creaste y más. |
| Trovit (Web Browser) https://casas.trovit.com.pe | 1. Buscador de casas en venta y en alquiler. 2. Ofrece promocionar distintos tipos de vivienda, con un buscador con filtros para facilidad de los usuarios. 3. Permite diferenciar entre venta y alquiler del espacio solicitado.

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td>
  </tr>
  <tr>
    <td colspan="5">Este análisis se realizó con la finalidad de poder identificar a nuestros potenciales competidores e idear estrategias y tácticas para diferenciarnos de estos.</td>
  </tr>
  <tr>
    <td colspan="3">(En la cabecera colocar por cada competidor nombre y logo)</td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        StudiStay
        <br>
        <div style="text-align: center; margin-top: 10px;">
                <img src="https://cdn.discordapp.com/attachments/1146490170917535764/1147743612243824691/logo.JPG" alt="StudiStay" width="70px">
        </div>
    <td colspan="1" valign="top" style="font-weight: bold;">
    Uniplaces
    <div style="text-align: center;">
                <img src="https://cdn.discordapp.com/attachments/1146490170917535764/1147749976819105812/uniplaces-logo-small.png" alt="Uniplaces" width="80px">
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;">
      HousingAnywhere
      <div style="text-align: center; margin-top: 20px;">
                <img src="https://cdn.discordapp.com/attachments/1146490170917535764/1147751201614606387/Housing_Anywhere_logo.png" alt="HousingAnywhere" width="80px">
            </div>
      </td>
    <td colspan="1" valign="top" style="font-weight: bold;" >
      Spotahome
      <div style="text-align: center; margin-top: 10px;">
                <img src="https://cdn.discordapp.com/attachments/1146490170917535764/1147751481978671144/th_main.png" alt="Spotahome" width="120px">
            </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">StudiStay une estudiantes con alojamiento ideal. Plataforma web innovadora agiliza búsqueda y fomenta comunidad. Simplificamos vivienda estudiantil, promoviendo crecimiento y conexiones en entorno enfocado.</td>
    <td colspan="1" valign="top">Uniplaces es un portal en línea para la reserva de alojamiento universitario. Con oficina central en Lisboa, el portal fue fundado en 2012 por el portugués Miguel Amaro, el argentino Mariano Kostelec y el británico Ben Grech.</td>
    <td colspan="1" valign="top">Housing Anywhere es una plataforma en línea de alojamiento enfocada a estudiantes internacionales. La startup radicada en Róterdam fue fundada en 2009 por Niels van Deuren, en aquel tiempo estudiante en la Escuela de Administración de Róterdam de la Universidad Erasmo de Róterdam.
</td>
    <td colspan="1" valign="top">Spotahome es una plataforma en línea que ofrece alquiler de pisos y habitaciones de media y larga estancia en 29 ciudades de Europa y Asia.</td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td colspan="1" valign="top">StudiStay destaca por su plataforma intuitiva, variedad de opciones de alojamiento y construcción de comunidades, brindando a los estudiantes comodidad, eficiencia y enriquecimiento en la búsqueda de alojamiento.</td>
    <td colspan="1" valign="top">Uniplaces ofrece alojamiento universitario diverso y seguro en línea. Búsqueda fácil, reserva conveniente, transparencia y asistencia multilingüe para estudiantes internacionales.</td>
    <td colspan="1" valign="top">Housing Anywhere ofrece a estudiantes internacionales alojamientos globales seguros y variados, con plataforma fácil, pagos seguros, interacción directa con arrendadores y apoyo multilingüe para una experiencia exitosa.</td>
    <td colspan="1" valign="top">Amplia cobertura, inspecciones virtuales, alquileres flexibles, seguridad, variedad, conveniencia. Adaptado para estancias prolongadas, brindando comodidad y confianza.
</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top">StudiStay abarca estudiantes universitarios y proveedores, simplificando la búsqueda de alojamiento con tecnología en diversas ubicaciones educativas, local e internacionalmente.
</td>
    <td colspan="1" valign="top">Estudiantes universitarios nacionales e internacionales buscando alojamiento cercano y adecuado en ciudades educativas en línea.
</td>
    <td colspan="1" valign="top">Estudiantes internacionales que necesitan alojamiento seguro y adaptable en múltiples destinos universitarios en todo el mundo.</td>
    <td colspan="1" valign="top">Estudiantes, jóvenes profesionales y viajeros que buscan alquileres de media y larga estancia en ciudades de Europa y Asia.</td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top">Publicidad en redes sociales y motores de búsqueda. Colaboración con universidades para promocionar la plataforma. Testimonios y reseñas de usuarios para generar confianza. Campañas de lanzamiento con ofertas especiales. Marketing de contenido sobre vida estudiantil y alojamiento.
</td>
    <td colspan="1" valign="top">Publicidad en universidades: Colaboraciones con 
    instituciones educativas para promocionar servicios. Marketing en redes sociales: Campañas dirigidas a estudiantes en plataformas como Instagram y Facebook. Contenido informativo: Blog y videos con consejos para estudiantes sobre alojamiento y vida universitaria.
</td>
    <td colspan="1" valign="top">Asociaciones universitarias: Colaboraciones con universidades para promocionar la plataforma entre estudiantes. Influencers estudiantiles: Colaboración con estudiantes influyentes en redes sociales para aumentar la visibilidad. Campañas de marketing de contenidos: Creación de guías y recursos para estudiantes internacionales.
</td>
    <td colspan="1" valign="top">Anuncios geográficamente segmentados: Publicidad en línea dirigida a ciudades específicas donde opera. Experiencia virtual: Enfatizar inspecciones virtuales y recorridos 360° en el marketing. Programas de referidos: Recompensar a usuarios que recomienden la plataforma a otros inquilinos potenciales.
</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">Plataforma alojamiento estudiantil. Opciones variadas, comunicación directa, información detallada, construcción de comunidades y experiencias enriquecedoras.</td>
    <td colspan="1" valign="top">Reserva de habitaciones y apartamentos universitarios en línea. Opciones de alojamiento diversificadas y adaptadas a las necesidades estudiantiles. Garantía de devolución de dinero en caso de discrepancias.
</td>
    <td colspan="1" valign="top">Plataforma de búsqueda y reserva de alojamiento a largo plazo. Inspecciones virtuales y fotos detalladas de propiedades. Seguridad en los pagos y verificación de propiedades.
</td>
    <td colspan="1" valign="top">Alquiler de pisos y habitaciones de media y larga estancia. Recorridos virtuales y descripciones exhaustivas de propiedades. Flexibilidad y adaptabilidad para estudiantes y profesionales.
</td>
  </tr>
  <tr>
    <td colspan="2">Precios y Costos</td>
    <td colspan="1" valign="top">Precios: Registro gratuito. Publicación de propiedades desde 10€. Comisión por reserva del 5% para proveedores. Costos: Desarrollo, marketing, soporte.
</td>
    <td colspan="1" valign="top">Precio de Reserva: Desde 50€ hasta 300€, según la ubicación y tipo de alojamiento. Comisión de Servicio: 5% del precio de reserva. Costos de Operación: Marketing (15,000€/mes), Soporte al Cliente (10,000€/mes), Desarrollo de Plataforma (20,000€/mes).</td>
    <td colspan="1" valign="top">Precio de Reserva: Varía según la duración y ubicación, desde 300€ al mes. Comisión de Plataforma: 10% del precio de reserva. Costos de Operación: Marketing (18,000€/mes), Seguridad en Pagos (8,000€/mes), Desarrollo de Tecnología (25,000€/mes).
</td>
    <td colspan="1" valign="top">Precio de Alquiler: Desde 500€ al mes para habitaciones y 1,000€ al mes para apartamentos. Comisión de Intermediación: 8% del primer mes de alquiler. Costos de Operación: Marketing (12,000€/mes), Inspecciones Virtuales (5,000€/mes), Equipo de Soporte (15,000€/mes).
</td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución</td>
    <td colspan="1" valign="top">Plataforma web accesible desde navegadores. Colaboración con instituciones educativas para promoción. Marketing en redes sociales y anuncios en línea.
</td>
    <td colspan="1" valign="top">Sitio web oficial: Plataforma en línea donde los estudiantes pueden buscar, ver y reservar alojamiento directamente. Colaboraciones universitarias: Asociaciones con universidades para promocionar el servicio entre los estudiantes. Marketing en redes sociales: Campañas en plataformas como Instagram y Facebook para llegar a su público objetivo. Afiliados y socios: Colaboración con agentes inmobiliarios y sitios web relacionados para ampliar la visibilidad.
</td>
    <td colspan="1" valign="top">Plataforma en línea: Sitio web donde los estudiantes pueden explorar opciones y realizar reservas. Colaboración universitaria: Asociaciones con instituciones educativas para promover la plataforma entre estudiantes internacionales. Programas de recomendación: Usuarios existentes pueden referir la plataforma a otros estudiantes. Publicidad en línea: Anuncios en redes sociales y motores de búsqueda para llegar a estudiantes potenciales.
</td>
    <td colspan="1" valign="top">Plataforma en línea: Sitio web donde los usuarios pueden buscar y reservar alojamiento a largo plazo. Marketing geográfico: Publicidad en línea específicamente dirigida a ciudades donde opera. Colaboraciones con intermediarios: Asociaciones con agencias inmobiliarias locales para ampliar la oferta de alojamiento. Estrategia de contenidos: Blogs, videos y recursos informativos para atraer tráfico y promocionar la plataforma.
</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">Equipo fundador especializado en Ingeniería de Software. Soluciones tecnológicas innovadoras para problemas diarios. Plataforma StudiStay: Interfaz intuitiva y amplia gama de opciones. Enfoque en conectar estudiantes y proveedores de alojamiento.
</td>
    <td colspan="1" valign="top">Amplia variedad de opciones de alojamiento. Plataforma intuitiva y fácil de usar. Garantía de devolución de dinero para seguridad del cliente.
</td>
    <td colspan="1" valign="top">Cobertura global en múltiples destinos universitarios. Inspecciones virtuales para comodidad de los usuarios. Relaciones con universidades para promoción.
</td>
    <td colspan="1" valign="top">Enfoque en alquileres de media y larga estancia. Ofrece inspecciones virtuales y detalles de propiedades. Adaptabilidad a diferentes necesidades de alojamiento.
</td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">Falta de reconocimiento de marca en el mercado. Dependencia de la aceptación de la plataforma por parte de los estudiantes y proveedores.
</td>
    <td colspan="1" valign="top">Competencia en el mercado de alojamiento estudiantil en línea. Dependencia de la reputación y confianza del sitio web.
</td>
    <td colspan="1" valign="top">Necesidad de mantener una plataforma tecnológicamente avanzada. Competencia en el espacio de alojamiento para estudiantes.
</td>
    <td colspan="1" valign="top">Posible desafío para mantener la calidad de las inspecciones virtuales. Dependencia de la reputación y confianza en la plataforma.
</td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">Alta demanda de soluciones tecnológicas en el sector de alojamiento estudiantil. Posibilidad de expandirse a otras soluciones relacionadas con la vida estudiantil. Crear una comunidad sólida entre estudiantes y proveedores.
</td>
    <td colspan="1" valign="top">Creciente demanda de alojamiento para estudiantes internacionales. Posibilidad de expansión a más ubicaciones universitarias.
</td>
    <td colspan="1" valign="top">Crecimiento del número de estudiantes internacionales. Expansión a nuevas ciudades y regiones.
</td>
    <td colspan="1" valign="top">Mayor demanda de alojamiento a largo plazo. Colaboraciones con intermediarios inmobiliarios.
</td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">Competencia de otras plataformas de búsqueda de alojamiento. Cambios en las preferencias de los estudiantes en cuanto a alojamiento. Riesgo de problemas técnicos o fallas en la plataforma.
</td>
    <td colspan="1" valign="top">Posible cambio en las preferencias de alojamiento de los estudiantes. Posible entrada de nuevos competidores en el mercado.
</td>
    <td colspan="1" valign="top">Cambios en las políticas de inmigración que afecten a la demanda. Posible aumento de la competencia de otras plataformas.
</td>
    <td colspan="1" valign="top">Competencia en el mercado de alquileres a largo plazo. Cambios en las preferencias de alojamiento de los estudiantes y profesionales.
</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

- Desarrollaremos nuestra aplicación y/o página web en la que minimizamos los posibles errores que se presenten, así los usuarios puedan tener una mejor experiencia de uso.

- Brindaremos un buen medio de comunicación entre los estudiantes y los arrendadores.

- Realizaremos encuestas a nuestros usuarios para conocer las características específicas que podemos mejorar.

- Pondremos en práctica un estudio de los competidores para evitar cometer sus errores.

- Recopilaremos información a través de revisiones de reseñas y comentarios de las características de nuestros competidores.


## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

**Preguntas generales:**

- ¿Cómo te llamas?
- ¿Cuántos años tienes?
- ¿Lugar de residencia?
- ¿A qué te dedicas actualmente?

**Preguntas sobre personalidad**

- ¿Te consideras una persona extrovertida o introvertida? ¿Por qué?

**Segmento 1: Estudiantes que buscan información sobre habitaciones:** 

- Actualmente, ¿qué tipo de lugar o habitación está buscando?
- ¿Qué características considera que debe poseer un sitio ideal en el que pueda alojarse?
- ¿Cuáles son los principales inconvenientes que se le presentan para poder encontrar una habitación cercana a su institución educativa?
- ¿Qué beneficios podría obtener al conseguir un lugar con las características que menciona?
- ¿Te sería de utilidad una aplicación en la que puedas encontrar este tipo de información?
- ¿Qué facilidades debería tener una aplicación que brinde información sobre habitaciones para estudiantes?


**Segmento 2: Arrendadores que buscan alquilar habitaciones** 

- Actualmente, ¿qué tipo de lugar o habitaciones ofrece al público, en especial a los estudiantes?
- ¿Qué características considera que debe poseer un sitio ideal en el que pueda alojarse?
- ¿Cuáles son los principales inconvenientes que se le presentan al momento de concretar los alquileres de las habitaciones?
- ¿Qué beneficios podría obtener al concretar los alquileres de manera más eficiente?
- ¿Te sería de utilidad una aplicación en la que puedas ofrecer las habitaciones que dispones?
- ¿Qué facilidades debería tener una aplicación en la que puedas conectarte con los estudiantes que necesitan una habitación para alojarse?

**Para mejorar la aplicación**
- ¿Qué te parece la idea de nuestro proyecto? ¿Te sería útil? 
- ¿Tienes sugerencias sobre posibles mejoras o características adicionales que podríamos integrar en nuestra aplicación?


### 2.2.2. Registro de entrevistas

<span style="font-size: 20px;">**Segmento 1: Estudiantes que buscan información sobre habitaciones.**</span>

**Entrevistado 1**

Nombres: Agustin Alejandro

Apellidos: Aguilar Lindo

Edad: 22 años

Distrito: Breña, Lima

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1146490170917535764/1147766383397048410/image.png" alt="Canvas"  width="90%"/>
</div>

Inicio: 00:04

Fin: 03:43

Enlace de la entrevista: [Entrevistas StudiStay](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202124061_upc_edu_pe/EX04GNgEu2lLpbYPuR_bdwYBfl78ai-GGNNCHW6hulVtxA?e=QNw6DY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjQuMjd9fQ%3D%3D)

Resumen de la entrevista:

Agustín, estudiante de Ingeniería de Sistemas, se autodefine como introvertido en situaciones con personas desconocidas, mientras que es extrovertido en compañía de sus amigos cercanos. En la actualidad, está en búsqueda de una habitación que le permita llegar rápidamente a la universidad. Sin embargo, se enfrenta a dificultades para encontrar el lugar adecuado, ya que en ocasiones las opciones incluyen servicios que no necesita y le cobran por ellos. Debido a esto, Agustín está en busca de un alojamiento que sea cómodo y asequible.La idea de contar con una aplicación especializada en la búsqueda de habitaciones le agrada mucho. Agustín considera esencial que esta aplicación tenga funcionalidades como filtros que le permitan especificar las características que busca en un cuarto y que le presente opciones según sus preferencias. En particular, valora la posibilidad de recibir recomendaciones personalizadas. Nuestra aplicación capturó completamente el interés de Agustín, ya que satisface exactamente lo que estaba buscando. Le gustaría que la aplicación le permita comunicarse mediante chat con los arrendadores, así como visualizar fotografías y reseñas de las habitaciones disponibles.


**Entrevistado 2**

Nombre: Fabio

Apellidos: Portella

Edad: 18 años

Distrito: Carabayllo, Lima

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1146490170917535764/1147767280609001532/image.png" alt="Canvas"  width="90%"/>
</div>

Inicio: 03:44

Fin: 08:37


Enlace de entrevista: [Entrevistas StudiStay](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202124061_upc_edu_pe/EX04GNgEu2lLpbYPuR_bdwYBfl78ai-GGNNCHW6hulVtxA?e=QNw6DY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjQuMjd9fQ%3D%3D)

Resumen de la entrevista:

Fabio Portella fue nuestro entrevistado, el cual es un estudiante universitario nos informa que en un futuro le gustaría encontrar una habitación cerca de su universidad para ir a pie o tomar transporte público. Además, las comodidades que busca son básicas como por ejemplo una cama, un baño dentro del dormitorio, una habitación para él solo, entre otras comodidades. Nos comenta que es difícil encontrar una habitación cerca de su universidad, que cumpla con sus comodidad y que se ajuste a su presupuesto. Las ventajas que Fabio encuentra en conseguir una habitación serían ahorrar tiempo, ya que no gastaría tantas horas de viaje y dinero en tomar transporte público. Al entrevistado le gustaría una aplicación la cuál lo ayudará en el proceso de búsqueda, comunicación con el arrendador, y mostrar las características y comodidades con las que cuenta el departamento o habitación.

**Entrevistado 3**

Nombre: Gianmarco Esteban

Apellidos: Quispe Chuchón 

Edad: 23 años

Distrito: Comas, Lima

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1146490170917535764/1147767736819273738/image.png" alt="Canvas"  width="90%"/>
</div> 

Inicio: 08:37

Fin: 12:48

Enlace de entrevista: [Entrevistas StudiStay](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202124061_upc_edu_pe/EX04GNgEu2lLpbYPuR_bdwYBfl78ai-GGNNCHW6hulVtxA?e=QNw6DY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjQuMjd9fQ%3D%3D)

Resumen de la entrevista:

Gianmarco, estudiante de Ingeniería de Software, está inmerso en la búsqueda de un alojamiento que cumpla dos condiciones esenciales: seguridad y proximidad a su universidad. Su preferencia apunta a una habitación simple y privada, con baño propio. No obstante, se enfrenta a un dilema común: encontrar una habitación que satisfaga estas necesidades sin incurrir en costos excesivos debido a la cercanía al campus. En este contexto, su objetivo se centra en hallar un equilibrio que le permita reducir gastos de transporte y garantizar su seguridad al mismo tiempo.

El entusiasmo de Gianmarco por la propuesta de nuestra aplicación es palpable. Identifica que no ha encontrado aún una solución adecuada para enfrentar este problema, lo que acentúa la importancia de nuestro proyecto. Además, su sugerencia de incluir experiencias de usuarios en la aplicación resalta la necesidad de contar con una fuente confiable de información al tomar decisiones sobre el alojamiento. Esta característica sería particularmente beneficiosa, ya que Gianmarco menciona que su familia de provincia a menudo se enfrenta a dificultades similares al buscar alojamiento en la capital. En este sentido, esta función no solo proporcionaría orientación a futuros inquilinos, sino que también evitaría situaciones adversas y malentendidos con los arrendadores.


<span style="font-size: 20px;">**Segmento 2**</span>

**Entrevistado 1**

Nombre:Sebastián Jesús

Apellidos: Ramírez Zapata

Edad: 22 años

Distrito: Santiago de Surco, Lima

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1146490170917535764/1147771836134866994/image.png" alt="Canvas"  width="90%"/>
</div> 

Inicio: 12:50

Fin: 20:37

Enlace de entrevista: [Entrevistas StudiStay](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202124061_upc_edu_pe/EX04GNgEu2lLpbYPuR_bdwYBfl78ai-GGNNCHW6hulVtxA?e=QNw6DY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjQuMjd9fQ%3D%3D)

Resumen de la entrevista:

La entrevista con Sebastián Jesús Ramírez Zapata se centra en su negocio de alquiler de habitaciones para estudiantes. Actualmente estudiante, previamente se dedicaba a ventas en línea. Ofrece tres viviendas, inspirado por su madre, quien alquila cerca de un instituto. Las habitaciones ideales deben ser de unos 3x3 metros, con cama, baño, internet y agua caliente. Obstáculos principales: precio y a veces internet. Ve potencial en una app para ofrecer habitaciones, como "StudiStay", desarrollada por él y su equipo. Busca que sea intuitiva y similar a apps de alojamiento, pero enfocada en estudiantes. Ve beneficios en un foro, calificaciones y comentarios para mejorar la comunicación. Considera que "StudiStay" agiliza la búsqueda de alojamiento, beneficiando tanto a arrendadores como estudiantes.

**Entrevistado 2**

Nombre: Carlos

Apellidos: Landeo

Edad: 26 años

Distrito: Santiago de Surco, Lima

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1146490170917535764/1147772204164055100/image.png" alt="Canvas"  width="90%"/>
</div>  

Inicio: 20:39

Fin: 28:32

Enlace de entrevista: [Entrevistas StudiStay](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202124061_upc_edu_pe/EX04GNgEu2lLpbYPuR_bdwYBfl78ai-GGNNCHW6hulVtxA?e=QNw6DY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjQuMjd9fQ%3D%3D)

Resumen de la entrevista:

Nuestro entrevistado fue Carlos Landeo, actual arrendador que trabaja para una pequeña empresa, y gracias a eso puede obtener el sustento necesario. Nos comentó que tiene experiencia con la renta de habitaciones hacia estudiantes. En base a esto, nos mencionó que lo más solicitado son espacios que cuentan con baño, cocina y un espacio cómodo, además de encontrarse en distritos seguros tales como San Isidro, La Molina o Santiago de Surco. Carlos dijo que uno de los principales inconvenientes que se le presentan es la pérdida de comunicación en las instancias finales de concretar un alquiler, por lo que le sería de gran utilidad una aplicación en la cual pueda publicitar los espacios que tenga en disponibilidad, además de poder comunicarse con los clientes de forma clara, sencilla y segura.

**Entrevistado 3**

Nombre: Yan Marcos

Apellidos: Soto Benavidez

Edad: 20 años

Distrito: Chorrillos, Lima

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1146490170917535764/1147772508511154266/image.png" alt="Canvas"  width="90%"/>
</div>  

Inicio: 28:34

Fin: 34:20

Enlace de entrevista: [Entrevistas StudiStay](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202124061_upc_edu_pe/EX04GNgEu2lLpbYPuR_bdwYBfl78ai-GGNNCHW6hulVtxA?e=QNw6DY&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjQuMjd9fQ%3D%3D)

Resumen de la entrevista:

Yan menciona que actualmente vive en Chorrillos y tiene espacios disponibles de su casa para poder arrendar como habitaciones y hasta un piso entero. Con respecto a los beneficios, menciona que puede brindar ambientes cómodos, amplios y con otros servicios como alimentación o pensión. Está comprometido y es consciente de que muchos estudiantes suelen perder tiempo en el tráfico en vez de estar en sus estudios o sufren algún tipo de riesgo cuando salen muy tarde de la universidad y él estaría encantado de poder ayudar a mitigar eso. Finalmente, menciona algunos posibles inconvenientes a la hora de realizar un arriendo y es que a veces pueden surgir temas legales, o no se entiende bien el contrato y entre otros problemas y sobre la aplicación comenta que le será de gran utilidad y su sugiere un sistema de calificaciones y perfiles para conocer mejor a sus clientes.

### 2.2.3. Análisis de entrevistas

Este análisis se centra en dos segmentos de usuarios clave: estudiantes universitarios que buscan habitaciones y propietarios interesados en alquilar habitaciones a estudiantes. A través de entrevistas detalladas con representantes de ambos segmentos, se explorarán sus necesidades y preferencias para crear perfiles de usuario y diseñar una aplicación de búsqueda de habitaciones eficaz.

**Segmento 1: Estudiantes que buscan información sobre habitaciones**

Los estudiantes universitarios en este segmento tienen como prioridades la proximidad a la universidad, comodidades básicas y seguridad al buscar habitación. Ven con buenos ojos una aplicación especializada que simplifique la búsqueda y confían en la información proporcionada por otros usuarios. Estas características son fundamentales para el diseño exitoso de una aplicación de búsqueda de habitaciones.

**Características Objetivas:**

- Proximidad a la Universidad: El 100% de los estudiantes busca alojamiento cercano a la universidad, lo que es un factor crucial en su elección.

- Comodidades Básicas: El 67% de los estudiantes busca comodidades básicas en sus habitaciones, como una cama y un baño privado.

- Dificultades en la Búsqueda: El 100% de los estudiantes menciona enfrentar dificultades en la búsqueda de alojamiento, lo que destaca la necesidad de una solución efectiva.
   
- Interés en Aplicaciones de Búsqueda: El 67% de los estudiantes muestra interés en utilizar aplicaciones para buscar alojamiento, indicando una disposición hacia la tecnología.

- Ahorro de Tiempo y Dinero: El 67% de los estudiantes enfatiza la importancia de ahorrar tiempo y dinero al buscar alojamiento cerca de la universidad.

- Seguridad: El 100% de los estudiantes valora la seguridad como un factor esencial en su elección de alojamiento.

- Confiabilidad de la Información: El 100% de los estudiantes resalta la importancia de contar con información confiable y reseñas verificadas en la aplicación.

**Características Subjetivas:**

- Personalidad Introvertida/Extrovertida: La aplicación puede adaptar las opciones de comunicación para satisfacer las preferencias individuales de los usuarios.

- Equilibrio entre Costo y Comodidad: La aplicación puede ofrecer herramientas para que los usuarios evalúen y comparen opciones en función de sus preferencias personales de seguridad y costo.

- Valoración de la Confianza: Incorporar sistemas de calificación y reseñas verificadas para fomentar la confianza entre inquilinos y arrendadores.

- Personalización: Utilizar algoritmos de recomendación que consideren las preferencias individuales de los usuarios, como la proximidad a la universidad o las comodidades deseadas.


**Segmento 2: Arrendadores que buscan alquilar habitaciones**

En este segmento, se analizaron entrevistas con arrendadores que buscan alquilar habitaciones a estudiantes, identificando características comunes que revelan sus necesidades y motivaciones. Estas características, que incluyen aspectos objetivos y subjetivos, son esenciales para diseñar una aplicación que mejore la experiencia tanto para los arrendadores como para los estudiantes en la búsqueda y oferta de alojamiento estudiantil.

**Características Objetivas:**

- Tipo de Habitación Ofrecida: Los arrendadores buscan ofrecer habitaciones con características específicas, como baño y cama.

- Ubicación Deseada: Algunos arrendadores tienen preferencias de ubicación, priorizando distritos seguros.

- Inconvenientes en la Comunicación: La comunicación efectiva en el proceso de arrendamiento es crucial, y algunos arrendadores enfrentan problemas en esta área.

- Espacios Comunes y Comodidades: Algunos arrendadores pueden ofrecer espacios comunes o comodidades adicionales en la vivienda para atraer a estudiantes en busca de un ambiente completo y conveniente.

**Características Subjetivas:**

- Experiencia y Motivación: La experiencia previa en negocios en línea y la motivación personal para alquilar habitaciones pueden impulsar la participación y la eficacia en la aplicación.

- Compromiso con la Comunidad Estudiantil: El compromiso de los arrendadores con la mejora de la experiencia de los estudiantes puede fomentar la colaboración en la plataforma.
 
- Enfoque en la Comunicación: La importancia de una comunicación efectiva con los clientes puede influir en la adopción y el éxito de la aplicación.

- Oferta de Servicios Adicionales: Los arrendadores que ofrecen servicios adicionales pueden utilizar la aplicación para promocionar y gestionar estos servicios de manera eficiente.


## 2.3. Needfinding
### 2.3.1. User Personas

**Segmento 1: Estudiantes que buscan información sobre habitaciones**

<img src="https://cdn.discordapp.com/attachments/1146490170917535764/1147937350203232386/Mario_Manrique.png"/>

**Segmento 2: Arrendadores que buscan alquilar habitaciones**

<img src="https://cdn.discordapp.com/attachments/1146490170917535764/1147937702092738662/Maria_Alvarez.png"/>

### 2.3.2. User Task Matrix

**Segmento Objetivo: Estudiantes que buscan información sobre habitaciones**

| Tarea | Frecuencia | Severidad | 
|:----|:----:|:----|
| Reunir información sobre la seguridad de la zona de alojamiento | Casi siempre | Alta |
| Comparar precios entre diferentes habitaciones | A veces | Media |
| Contactarse con los arrendadores | A veces | Media |
| Evaluar las características de las habitaciones | Casi siempre | Alta |
| Investigar habitaciones cerca de su institución educativa | Siempre | Alta |
| Evaluar las comodidades que brinda el arrendador | A veces | Media |


**Segmento Objetivo: Arrendadores que buscan alquilar habitaciones**

| Tarea | Frecuencia | Severidad | 
|:----|:----:|:----|
| Gestionar las propiedades que posee | Siempre | Alta |
| Contactarse con los posibles clientes | A veces | Alta |
| Evaluar los beneficios del contrato | Casi siempre | Media |
| Adquirir información sobre propiedades | Casi siempre | Media |
| Diseñar publicidad de las habitaciones | A veces | Media |
| Buscar medios dónde publicitar sus habitaciones | Casi siempre | Media |


### 2.3.3. User Journey Mapping

**Segmento Objetivo: Estudiantes que buscan información sobre habitaciones**

<img src="https://i.imgur.com/wUdOmmi.png"/>

**Segmento Objetivo: Arrendadores que buscan alquilar habitaciones**

<img src="https://i.imgur.com/LVHm6XA.png"/>

### 2.3.4. Empathy Mapping

<img src="https://i.imgur.com/pIULvmZ.png"/>

### 2.3.5. As-is Scenario Mapping

<img src="https://i.imgur.com/fDMMJZL.png"/>

<br><br>

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.
## 3.2. User Stories.
## 3.3. Impact Mapping.
## 3.4. Product Backlog.

# Capítulo IV: Product Design

## 4.1. Style Guidelines.

### 4.1.1. General Style Guidelines.
En esta sección se analizará los diseños que se consideraron para nuestra marca. Debido a que es importante expresar las intenciones que tenemos con nuestros clientes. Además, se tendrá en cuenta que la tipografía y composición adopten un tono Casual/Formal, esto teniendo en cuenta nuestro público objetivo.

**-Logo:** 
Nuestro logo está conformado por dos imágenes principales, las cuales son una casa y un árbol, esto hace referencia al servicio que se está brindando (el cual es la renta de habitaciones). Los colores usados fueron derivados del azul y blanco, el cual crea una paleta de colores que hace alusión a la paz, tranquilidad y seriedad, y refuerza la confianza de nuestros usuarios en el servicio que se brindará.
![Logo](https://media.discordapp.net/attachments/1146490170917535764/1147743612243824691/logo.JPG)

**-Tipografía:**
Se requirió dos tipos de tipografías claras, legibles y fáciles de leer en diferentes dispositivos. Fueron seleccionadas Poppins y Jost.
![cuadro01](https://media.discordapp.net/attachments/1146490170917535764/1148327842019557407/Captura_de_pantalla_2023-09-04_134346.jpg)

**-Colores empleados:**
Para la elección de colores, se tuvo en cuenta el propósito de la aplicación y el servicio y lo que esta debería transmitir al usuario. 

![cuadro02 ](https://media.discordapp.net/attachments/1146490170917535764/1148338251543888053/Captura_de_pantalla_2023-09-04_142543.jpg)
![cuadro03](https://media.discordapp.net/attachments/1146490170917535764/1148338251313188905/Captura_de_pantalla_2023-09-04_142346.jpg)


**-Íconos:** 
Con respecto a la parte de los iconos, estos serán simples y minimalistas para transmitir la información de manera sencilla y eficiente. Estos deben de adaptarse perfectamente a la interfaz de la aplicación, ocupando un espacio óptimo sin comprometer la legibilidad. Es por ello que su diseño minimalista ayuda a evitar la sobrecarga visual y permite una navegación fluida. Para este caso se usarán los íconos: Tabler-Icons
![Cuadro04](https://media.discordapp.net/attachments/1146490170917535764/1148339213637525626/Captura_de_pantalla_2023-09-04_142940.jpg)


### 4.1.2. Web Style Guidelines.
En esta sección se explicará el estilo y patrón que hace uso nuestra interfaz tanto del landing page y la aplicación web.
**-Landing Page:** Esta utiliza el Patrón Z, una estructura diseñada para guiar al usuario por la página de manera natural y efectiva. En la parte superior se encontrará la barra de navegación con un tono oscuro, que brinda un aspecto serio y confiable. Esta barra contiene el logo y secciones como "Servicios", "Quiénes somos", "Testimonios" y "Aplicación". Se usaron colores derivados del azul el cual añade un toque de seriedad y paz al diseño y contrasta con el resto de la página para invitar al usuario a descargar y probar la aplicación.

![Cuadro05](https://media.discordapp.net/attachments/1146490170917535764/1148339886923972658/Captura_de_pantalla_2023-09-04_143224.jpg)

## 4.2. Information Architecture.
En esta sección, estableceremos la estructura y forma del software en relación a nuestros segmentos objetivos, así como los elementos y características que se usarán dentro de la navegación de la aplicación.
### 4.2.1. Organization Systems.
Para crear la sección del Landing Page y la Aplicación web, hemos utilizado una estructura visual jerárquica en la página web, lo que nos permite asignar la ubicación apropiada a cada elemento necesario en este desarrollo. Para lograrlo, se considerarán factores como etiquetas, especificaciones de pantalla y resolución. Además, se diseñarán íconos utilizando una matriz, lo que optimizará la visualización de los detalles y contribuirá a mantener un proceso ordenado en todo momento.

**Segmento Objetivo: Estudiantes que buscan información sobre habitaciones**

- Jerárquica:
  - Al aplicar los filtros adecuados, los espacios, habitaciones o departamentos elegidos pueden aparecer con el debido orden, es decir, los artículos con mayor coincidencia aparecerán en primer lugar y así sucesivamente. El usuario tendrá la posibilidad de elegir el resultado de su agrado.
- Secuencial:
  - Para la creación de una cuenta para el uso de la aplicación, la información mostrada en pantalla deberá seguir una secuencia, en el que se deben respetar los pasos necesarios para que se pueda lograr con el cometido.
- Matricial:
  - En la configuración de la cuenta, los usuarios podrán configurar distintos aspectos de la misma de acuerdo a sus preferencias, mostrando los apartados divididos en secciones.



**Segmento Objetivo: Arrendadores que buscan alquilar habitaciones**

- Jerárquica: 
  - Cuando se desee publicar artículos organizados por categorías, podrá elegir el orden en el que quiera que se visualice para los estudiantes, por lo que se presentará de forma ordenada.

- Secuencial: 
  - Para la creación de una cuenta para el uso de la aplicación, la información mostrada en pantalla deberá seguir una secuencia, en el que se deben respetar los pasos necesarios para que se pueda lograr con el cometido.

- Matricial: 
  - En la configuración de la cuenta, los usuarios podrán configurar distintos aspectos de la misma de acuerdo a sus preferencias, mostrando los apartados divididos en secciones. 

### 4.2.2. Labeling Systems.
A continuación, se mostrará el sistema de etiquetado que otorgará una descripción breve y clara de la información mostrada en nuestra Landing Page.

Tenemos los siguientes encabezados:

 - Home: En esta sección se muestra la sección inicial de la Landing Page, en la que se ofrece la bienvenida a los posibles usuarios, junto a una frase que representa al proyecto.
 - Servicios: En esta sección se describen las características que los usuarios podrán encontrar al hacer uso de nuestra aplicación.
 - Quiénes somos: En esta sección el cliente puede observar información acerca de nuestro equipo de desarrollo y una descripción breve de nuestro objetivo.
 - Testimonios: En esta sección se pueden visualizar las opiniones de los usuarios que probaron el servicio, además de la puntuación que brindaron.
 - Descargar: En esta sección se puede visualizar las opciones de descarga que podrán estar disponibles en un posible futuro al desarrollar una versión para dispositivos móviles.

### 4.2.3. SEO Tags and Meta Tags

Estas etiquetas son esenciales para mejorar la visibilidad de la aplicación web en los motores de búsqueda como Google. Las etiquetas SEO incluyen palabras clave relevantes y descripciones concisas para que los motores de búsqueda indexen y clasifiquen el contenido de la aplicación de manera efectiva. Las metaetiquetas proporcionan información adicional sobre la página, como el título y la descripción que se muestran en los resultados de búsqueda.

**Para el Landing Page:**

Tittle: StudiStay
Description: StudiStay -  StudiStay Connect Official Landing Page 
Keywords: apartment, students, rent apartment
Authors: StudiStay Connect team

**Para la aplicación web:**

Tittle: StudiStay
Description: StudiStay -  StudiStay Connect Official Web Page
Keywords: apartment, students, rent apartment, low prices, web courses
Authors: StudiStay Connect team

### 4.2.4. Searching Systems.
 - Landing Page: Los usuarios podrán hacer uso de la barra de navegación ubicada en la parte superior, para poder ubicarse en los distintos apartados en los que está dividido nuestra página, siendo una forma didáctica para interactuar con esta.

 - Aplicación Web: Por parte de los estudiantes, tendrán la opción de realizar búsquedas de espacios ideales para ellos, por medio de aplicar los filtros necesarios tales como precio, tamaño, lugar, etc. Los resultados serán mostrados de acuerdo a la coincidencia con la búsqueda establecida. Por parte de los arrendadores, podrán buscar a los clientes con quienes contactaron para realizar un alquiler, por medio de filtros como fecha, lugar, etc.



### 4.2.5. Navigation Systems.
A continuación, el equipo mostrará los sistemas de navegación con los que contará nuestro servicio para permitir a los usuarios navegar de manera sencilla y eficiente a cualquier sección de información.

En nuestro Landing Page, encontramos la sección de la barra de navegación en la parte superior, la cual nos permite navegar directamente a un apartado dentro de la página. Esta barra de navegación será visible en todo momento, para que el usuario pueda dirigirse a otra sección que desee visualizar. De esta manera, generamos una navegación más fluida y dinámica para el usuario.

En nuestra aplicación web, utilizaremos un proceso similar al descrito, con diversas opciones que variarán de acuerdo al segmento objetivo que esté utilizando el servicio. Estos podrán hacer uso de filtros para poder encontrar de mejor manera la información precisa que necesiten.


## 4.3. Landing Page UI Design.

### 4.3.1. Landing Page Wireframe.

![m1](https://media.discordapp.net/attachments/1146490170917535764/1148344163218243655/01.jpg)
![m2](https://media.discordapp.net/attachments/1146490170917535764/1148344163478278164/02.jpg)
![m3](https://media.discordapp.net/attachments/1146490170917535764/1148344163801243759/03.jpg)
![m4](https://media.discordapp.net/attachments/1146490170917535764/1148344164107436122/04.jpg)
![m5](https://media.discordapp.net/attachments/1146490170917535764/1148344164497494046/05.jpg)

[Enlace a Figma "Ver Diseños"](https://www.figma.com/file/ceXZ987xbS3HnR0A1ISTwf/Mockups?type=design&node-id=0%3A1&mode=design&t=HcpJIjoBHU1Hyp6C-1)

### 4.3.2. Landing Page Mock-up.

![m01](https://media.discordapp.net/attachments/1146490170917535764/1148347277824491660/001.jpg)
![m02](https://media.discordapp.net/attachments/1146490170917535764/1148347278558494770/002.jpg)
![m03](https://media.discordapp.net/attachments/1146490170917535764/1148347279217000479/003.jpg)
![m04](https://media.discordapp.net/attachments/1146490170917535764/1148347279544172604/004.jpg)
![m05](https://media.discordapp.net/attachments/1146490170917535764/1148347279774863453/005.jpg)

**Version Mobile**

![m0001](https://media.discordapp.net/attachments/1146490170917535764/1148347277572853831/0001.jpg)
![m0002](https://media.discordapp.net/attachments/1146490170917535764/1148347278206193794/0002.jpg)
![m0003](https://media.discordapp.net/attachments/1146490170917535764/1148347278847918090/0003.jpg)

[Enlace a Figma "Ver Diseños"](https://www.figma.com/file/ceXZ987xbS3HnR0A1ISTwf/Mockups?type=design&node-id=0%3A1&mode=design&t=HcpJIjoBHU1Hyp6C-1)

## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.

![m001]()
![m002]()
![m003]()
![m004]()
![m005]()

[Enlace a Figma "Ver Diseños"](https://www.figma.com/file/ceXZ987xbS3HnR0A1ISTwf/Mockups?type=design&node-id=45%3A255&mode=design&t=HcpJIjoBHU1Hyp6C-1)

### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.
### 4.4.3. Web Applications User Flow Diagrams.
### 4.5. Web Applications Prototyping.

## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
### 4.6.2. Software Architecture Container Diagrams.
### 4.6.3. Software Architecture Components Diagrams.

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
### 4.7.2. Class Dictionary.

## 4.8. Database Design.
### 4.8.1. Database Diagram.

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
### 5.1.2. Source Code Management.
### 5.1.3. Source Code Style Guide & Conventions.
### 5.1.4. Software Deployment Configuration.

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint n
#### 5.2.1.1. Sprint Planning n.
#### 5.2.1.2. Sprint Backlog n.
#### 5.2.1.3. Development Evidence for Sprint Review.
#### 5.2.1.4. Testing Suite Evidence for Sprint Review.
#### 5.2.1.5. Execution Evidence for Sprint Review.
#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
#### 5.2.1.8. Team Collaboration Insights during Sprint.
