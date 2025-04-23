# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo
| **Nombre**             | **Moovit**                                                                                                                                   | **RedBus**                                                                                             | **QuickRide**                                                                                                          | **Frock (propuesta)**                                                                                                                                   |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Overview**           | Plataforma global para planificar viajes en transporte público, incluyendo colectivos y buses, con mapas, horarios y rutas.                 | Plataforma digital de compra de pasajes en buses interprovinciales en LATAM y Asia.                   | App india para compartir viajes al trabajo (carpooling) entre particulares con rutas fijas.                           | Plataforma enfocada en el transporte colectivo informal interurbano en zonas rurales y periféricas de Perú. Informa sobre paraderos, rutas, disponibilidad y tarifas. |
| **Ventajas Competitivas** | Amplia cobertura internacional, mapas en tiempo real, integración con transporte formal e informal.                                         | Facilita pagos seguros y reservas anticipadas, alianzas con empresas de buses formales.               | Permite compartir autos con rutas definidas entre compañeros de trabajo, bajo costo y menor congestión.              | Adaptación cultural y tecnológica al entorno rural y periférico peruano, interfaz sin registro obligatorio, visibilidad de conductores informales, enfoque flexible e inclusivo. |
| **Modelo de Negocio**  | Freemium para usuarios, venta de datos a operadores de transporte y gobiernos.                                                              | Comisión por pasaje vendido, acuerdos con empresas de transporte.                                     | Comisión por viaje compartido, modelo B2C y B2B.                                                                      | Modelo freemium: gratuito para usuarios, monetización a futuro por suscripciones o tarifas a conductores u organizaciones aliadas.                  |
| **Usuarios Objetivo**  | Usuarios urbanos y suburbanos que usan transporte público.                                                                                  | Usuarios que viajan entre ciudades con servicios de buses formales.                                   | Profesionales que comparten auto en horarios laborales.                                                               | Pasajeros de zonas rurales o periurbanas (20-60 años), conductores informales independientes, municipios o asociaciones de transporte.              |
| **Tecnologías Clave**  | GPS, API de mapas, predicción de llegada, alertas de tráfico.                                                                               | Pasarela de pago, integración con operadores formales.                                                 | Geolocalización, agrupación por rutas y horarios.                                                                    | GPS, interfaz simple y perfiles verificados de conductor, mapeo colaborativo de rutas y paraderos.                                                  |
| **Debilidades**        | Requiere conectividad constante, enfoque urbano.                                                                                            | No cubre colectivos ni rutas informales.                                                               | Limitado a carpooling urbano, no apto para zonas rurales.                                                             | Depende de la adopción digital en zonas con conectividad limitada; requiere mapeo inicial colaborativo.                                             |

### 2.1.2. Estrategias y tácticas frente a competidores
## 2.2. Entrevistas
#### 2.2.1. Diseño de entrevistas
#### **Preguntas generales**

- ¿Cuál es su nombre?

- ¿Cuántos años tiene?

- ¿Cuál es su profesión?

- ¿En qué ciudad vive?

#### **🎯 Para usuarios**
- ¿Por qué eliges colectivo y no otra forma de transporte?

- ¿Has llegado a perder tiempo o equivocarte de lugar por no tener información?

- ¿Cómo sueles enterarte de qué colectivo tomar?

- ¿Alguna vez has tenido problemas para encontrar un paradero?

- ¿Te gustaría una app que te muestre los paraderos y rutas? ¿Qué te gustaría ver?

- ¿Qué tan confiable consideras la información que ves en redes o te dicen otros?

- ¿Te sentirías más tranquilo si pudieras ver esa info en un mapa antes de salir?

- ¿Sabes aproximadamente cuánto demora en salir un auto? ¿Te incomoda esperar?

- ¿Cómo sabes si todavía hay autos disponibles en ciertas horas?

- ¿Qué te gustaría ver en una app de colectivos? (rutas, horarios, mapas, precios, fotos…)

#### **🚖 Líderes de ruta:**

- ¿Cómo se decide cuándo sale cada auto?

- ¿Cuántos autos hay normalmente en la ruta?

- ¿Cómo se organizan los horarios y salidas?

- ¿En qué horarios hay más movimiento?

- ¿Los pasajeros te llaman? ¿Llegan directo al paradero?

- ¿Cómo se enteran los pasajeros de dónde están ustedes?

- ¿Alguna vez te han dicho que se perdieron o que no encontraron el paradero?

- ¿Te molestaría si alguien pone tu paradero en una app?

- ¿Tú mismo estarías dispuesto a dar información actualizada de horarios o rutas?

- ¿Preferirías que lo haga otra persona o tener una persona que te apoye?

- ¿Te interesaría aparecer como “empresa recomendada”?

#### 2.2.2. Registro de entrevistas
| **Nombre** | **Fecha** | **Duración** | **Tipo** | **Notas**|
|------------|-----------|--------------|----------|----------|
#### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
#### 2.3.1. User Personas
#### 2.3.2. User Task Matrix
#### 2.3.3. User Journey Mapping
| Etapa                   | Emoción        | Diálogo                                                                                           | Descubrimiento e instalación                                | Exploración de funciones                                         | Uso de funciones clave                                                                | Interacción en tiempo real                                                             | Después del viaje                                                  |
|------------------------|----------------|----------------------------------------------------------------------------------------------------|-------------------------------------------------------------|------------------------------------------------------------------|----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| Descubrimiento         | Curiosidad     | “Escuché que con esta app puedo saber dónde tomar el colectivo.”                                  | Descubre Frock por recomendación o redes sociales.          | Ingresa a la tienda de apps, revisa imágenes y descripción.      | Descarga la app y permite acceso a ubicación.                                          | Recibe notificación de bienvenida con guía rápida.                                     | -                                                                  |
| Investigación          | Interés        | “¿Será confiable? ¿Tendrá los horarios y precios claros?”                                         | Ve opiniones en redes sociales o grupos vecinales.          | Lee reseñas y puntuaciones de usuarios en la app store.          | Explora las secciones de preguntas frecuentes, seguridad y términos de uso.           | Revisa demos o tutoriales interactivos dentro de la app.                               | -                                                                  |
| Búsqueda               | Expectativa    | “¿Dónde están los paraderos más cercanos? ¿Cuánto me costará?”                                    | Abre la app por primera vez.                                | Se ubica en el mapa automático según su localización.            | Busca paraderos cercanos, tarifas y tiempo estimado según ruta seleccionada.           | Visualiza en tiempo real el trayecto de colectivos cercanos.                          | Guarda sus rutas favoritas para uso futuro.                                           |
| Reserva                | Confianza      | “¡Listo! Ya sé cuántos minutos faltan para que pase, si hay asientos y en qué paradero abordar.”  | Recibe sugerencias basadas en historial de uso o ubicación. | Ve rutas sugeridas con información de asientos disponibles.      | Selecciona el colectivo más conveniente y reserva un asiento disponible si aplica.     | Muestra en tiempo real cuántos minutos faltan, disponibilidad de asientos y paradero exacto. | Recibe confirmación visual y sonora con QR para abordar.                             |
| Personalización        | Entusiasmo     | “Voy a elegir el que tenga aire acondicionado y llegue más rápido.”                               | Accede a perfil para ajustar preferencias.                  | Activa filtros: aire acondicionado, accesibilidad, horario, calificación del conductor.| Compara varias opciones en una misma ruta con detalles de comodidad y disponibilidad. | Ve recomendaciones según sus elecciones anteriores o preferencias marcadas.            | La app guarda su configuración para futuras reservas.                                 |
| Experiencia de Servicio| Satisfacción   | “¡Llegué cómodo, a tiempo y sin complicaciones!”                                                  | Recibe notificaciones automáticas para salir a tiempo.      | Consulta de nuevo la app para confirmar detalles del viaje.      | Aborda el colectivo mostrando su pase digital (QR).                                     | Verifica asiento asignado, sigue el trayecto en tiempo real desde su móvil.            | Finaliza el viaje y recibe agradecimiento automático.                                |
| Post-servicio          | Apreciación    | “Voy a recomendar esta app. Me ahorró tiempo y fue súper clara.”                                  | Recibe mensaje de cierre del viaje con resumen.             | Visualiza estadísticas personales de uso (viajes, ahorro de tiempo, etc.).            | Recibe invitación para calificar el servicio.                                          | Comparte su experiencia con amigos o en redes desde un botón en la app.                | Deja una reseña y activa alertas para futuros viajes.                                |

#### 2.3.4. Empathy Mapping
#### 2.3.5. As-is Scenario Mapping
## 2.4. Ubiquitous Language
El lenguaje ubicuo es una parte fundamental de la estrategia de UX. Se refiere al conjunto de términos y frases que, aunque no pertenecen al contexto técnico del desarrollo, se utilizan para expresar la lógica del negocio. Esto permite que todos los involucrados en el proyecto, incluidos los usuarios finales, puedan entender y participar mejor en el desarrollo del producto.

## Glosario

**Colectivo (Vehículo Compartido):**  
Automóvil que opera en rutas fijas entre pueblos o distritos, transportando varios pasajeros a la vez. Son esenciales en zonas rurales o alejadas, donde no hay transporte formal constante.

**Whereabouts (Paradero):**  
Punto habitual donde los colectivos recogen o dejan pasajeros. No siempre está señalizado oficialmente, pero es reconocido por los usuarios locales. En la plataforma, se geolocaliza para ofrecer visibilidad.

**Route (Ruta):**  
Trayecto fijo que sigue un colectivo, desde un punto de partida hasta un destino, pasando por una serie de paraderos. Las rutas pueden variar según el conductor o la demanda, pero mantienen un patrón general.

**Route request (Request):**  
Acción del usuario para conocer o solicitar información sobre una ruta específica, ya sea para planear su viaje o encontrar un colectivo disponible.

**Verified driver (Conductor Verificado):**  
Persona que opera un colectivo y que ha sido registrada en la plataforma mediante un proceso de verificación de identidad y datos del vehículo, brindando mayor confianza al usuario.

**Driver´s profile (Perfil del Conductor):**  
Información pública del conductor disponible en la plataforma, incluyendo nombre, foto, vehículo, calificación y comentarios de otros pasajeros, aumentando la confianza y seguridad del servicio.

**Availability (Disponibilidad):**  
Estado en el que un conductor está activo y visible para los usuarios de la aplicación. Indica que está en ruta, con cupos disponibles, y permite recibir solicitudes o ser ubicado por los pasajeros.

**Viaje (Ride):**  
Servicio individual que ocurre cuando un pasajero aborda un colectivo en una ruta específica. Puede ser monitoreado en tiempo real si hay conectividad disponible.

**Fare(Tarifa):** 
Costo estimado del viaje, determinado con base en la distancia, ruta y condiciones locales. Aunque el pago final puede variar, sirve como referencia para los usuarios.

**Monitoring (Monitoreo):**  
Supervisión del estado y movimiento de los colectivos registrados. Esto incluye el seguimiento de rutas activas, paraderos más frecuentados y tiempo estimado de llegada para mejorar la experiencia del usuario.

**Coverage areas (Zonas de Cobertura):**  
Áreas geográficas donde opera el servicio de colectivos registrados en la plataforma. Ayuda a delimitar las regiones con rutas disponibles y mejorar la planificación de nuevas expansiones.
