# Trabajo final DIU 2025/26

**Portfolio UX y propuesta de diseño para ECO MERCADO UGR**  
Autor: Alberto David Gómez Gijón  
Repositorio base de prácticas: [Mercenari23/UX_CaseStudy](https://github.com/Mercenari23/UX_CaseStudy.git)  
Fecha de elaboración: 14 de junio de 2026

## Resumen

Este documento resuelve las dos partes del trabajo final de Diseño de Interfaces de Usuario. La primera parte recoge una autoevaluación razonada de la experiencia adquirida durante la asignatura a partir del proyecto PogoRamen y de las prácticas desarrolladas. La segunda parte aplica esa experiencia a un caso real: el diseño de una propuesta de valor para el ECO MERCADO UGR, tomando como referencia iniciativas existentes de mercado ecológico y consumo de proximidad.

La entrega se apoya en los materiales ya documentados en el repositorio: investigación de usuarios, análisis competitivo, personas, journey maps, wireframes, diseño visual, mockups, pruebas de evaluación, SUS, A/B testing y conclusiones. Como resultado adicional de la Parte II se incluye un boceto navegable en HTML: [`mockups/ecomercado-ugr-web.html`](mockups/ecomercado-ugr-web.html).

## Parte I: Mi experiencia UX

Mi experiencia en la asignatura de Diseño de Interfaces de Usuario ha sido especialmente útil porque me ha obligado a pasar de una forma intuitiva de diseñar a una forma más justificada, medible y orientada a usuarios reales. Antes de trabajar con la metodología vista en clase, muchas decisiones de interfaz podían parecer correctas simplemente porque visualmente resultaban atractivas o porque encajaban con una idea inicial. Sin embargo, el desarrollo del caso PogoRamen me ha mostrado que una propuesta de UX solo es sólida cuando se puede explicar desde evidencias: necesidades del usuario, objetivos de negocio, contexto de uso, limitaciones cognitivas, accesibilidad, arquitectura de información y evaluación posterior.

La primera aportación destacable fue la definición del concepto de PogoRamen. La idea inicial era crear un restaurante temático inspirado en Pokémon y comida japonesa, pero el trabajo de UX ayudó a convertir esa idea en una experiencia de usuario concreta. No se trataba únicamente de decorar una web con una estética de anime, sino de transformar el acto de pedir comida en una interacción comprensible y memorable. La metáfora del "PC Pokémon" y del "equipo de 6" ingredientes fue una de las decisiones más importantes, porque conectaba directamente el universo temático con una tarea real: construir un plato personalizado. Esta relación entre metáfora y acción es lo que aporta valor desde el punto de vista de UX. Si la metáfora hubiera sido solo ornamental, habría aumentado la carga cognitiva; al estar ligada a la selección de ingredientes, ayuda a recordar el flujo y a hacerlo más divertido.

En la fase de investigación aprendí la importancia de no diseñar únicamente desde mis preferencias personales. El User Research Plan y el análisis competitivo permitieron observar referentes reales como Hanazono, Ramen Shifu y Otaku Ramen. A partir de ellos entendimos que los restaurantes temáticos suelen tener dos tensiones: por un lado necesitan identidad visual fuerte para atraer y ser compartibles; por otro, no deben sacrificar claridad en carta, reservas, alérgenos o proceso de pedido. Mi aportación en esta fase fue identificar que la tematización debía ser funcional. La interfaz debía ayudar a elegir, no convertirse en una capa visual que dificultara la tarea principal.

El análisis competitivo también me ayudó a entender mejor el concepto de benchmark. Comparar alternativas no consiste en copiar pantallas ni enumerar características, sino en detectar patrones, puntos fuertes y debilidades. En nuestro caso, Ramen Shifu parecía más claro y eficiente, mientras que propuestas más orientadas al fandom podían resultar más inmersivas pero menos directas. Esa lectura nos permitió situar PogoRamen en un punto intermedio: una experiencia temática, pero con una estructura de pedido guiada.

La creación de personas y journey maps fue otro aprendizaje central. Las personas ficticias, como Alex y Manuel, sirvieron para representar necesidades distintas: usuarios jóvenes con afinidad por la cultura pop, usuarios que buscan rapidez, personas que pueden sentirse atraídas por la estética, pero también usuarios que necesitan orientación y seguridad durante el proceso. El journey map nos obligó a pensar en emociones, expectativas y momentos de fricción, no solo en pantallas. Esta práctica mejoró mi capacidad para imaginar el producto como una secuencia de decisiones del usuario. Por ejemplo, una pantalla de inicio atractiva no es suficiente si luego el usuario no sabe cómo volver atrás, dónde revisar su pedido o qué ingredientes ha seleccionado.

En la revisión de usabilidad se produjo uno de los aprendizajes más prácticos. La valoración obtenida, 56 en nivel moderado, hizo visible que una interfaz puede tener buenas ideas y aun así necesitar mejoras objetivas. Entre los problemas detectados estaban la falta de formularios, la ausencia de buscador, la poca ayuda contextual, mensajes de error insuficientes, problemas de contraste y navegación mejorable. Esta parte me enseñó que la evaluación no debe entenderse como una crítica negativa, sino como una herramienta para priorizar. La usabilidad deja de ser una opinión cuando se transforma en criterios observables: legibilidad, feedback, control del usuario, prevención de errores, consistencia y facilidad de recuperación.

En la fase de ideación y reframing aprendí a traducir problemas en oportunidades. El feedback capture grid y el empathy map nos ayudaron a reformular el reto: no queríamos "hacer otro restaurante anime", sino diseñar una experiencia gastronómica temática que fuera inmersiva, comprensible, personalizada y fácil de usar. Esa reformulación fue importante porque cambió el foco desde el producto hacia la experiencia. El usuario no solo compra comida; busca una actividad social, visualmente compartible y coherente con una identidad cultural. Al mismo tiempo, necesita información clara sobre ingredientes, alérgenos, precio y estado del pedido.

El ScopeCanvas fue útil para delimitar el MVP. En proyectos creativos es fácil querer incluir demasiadas funciones: comunidad, recompensas, menús especiales, pedidos anteriores, redes sociales, reservas, carta, estado del pedido y personalización avanzada. El canvas ayudó a separar lo imprescindible de lo secundario. Para una primera versión, el núcleo debía estar en explorar carta, crear el "equipo de 6", revisar ingredientes, añadir al pedido y consultar recompensas. Esta decisión me hizo entender que un buen diseño también consiste en renunciar temporalmente a funciones que pueden distraer del objetivo principal.

La arquitectura de información y el labelling fueron fases donde mejoré mi sensibilidad hacia el lenguaje. Términos como "crear tu equipo", "menús entrenadores", "ligas regionales" o "tarjeta de medallas" encajan con la temática, pero deben ser suficientemente claros para usuarios que no conozcan todos los códigos del universo Pokémon. La lección principal fue que el etiquetado debe equilibrar identidad y comprensión. Un nombre creativo puede mejorar la experiencia si se entiende, pero puede perjudicarla si obliga al usuario a interpretar demasiado. Por eso conviene combinar etiquetas temáticas con apoyos visuales o microcopy breve.

Los wireframes fueron una contribución relevante porque nos permitieron separar estructura de estética. Antes de aplicar color, tipografía o imágenes, trabajamos pantallas como el menú principal, la creación del equipo, entrenadores, ligas, carrito, login, medallas y web de usuario. Esta fase me ayudó a ver que un wireframe no es un dibujo pobre, sino una herramienta de decisión. Permite comprobar jerarquía, flujo, agrupación de información y puntos de acción sin distraerse con el acabado visual.

En la fase visual aprendí a aplicar Atomic Design de una forma práctica. Definir átomos, moléculas y organismos nos permitió organizar botones, chips, campos, medallas, slots de ingredientes, tarjetas y módulos completos como el constructor del equipo o el carrito. Esta metodología me parece una de las aportaciones más valiosas de la asignatura porque conecta diseño y desarrollo. Si los componentes están bien pensados, la interfaz es más consistente, más fácil de mantener y más fácil de escalar. En PogoRamen, los slots del "equipo de 6" y las medallas no son elementos decorativos aislados, sino piezas reutilizables que refuerzan la experiencia.

La evaluación final mediante usuarios ficticios, SUS y A/B testing completó el ciclo de diseño centrado en usuario. Al comparar PogoRamen con Wall Street Burguer observamos que ambos proyectos tenían propuestas creativas, pero con niveles distintos de carga cognitiva. PogoRamen obtuvo una media SUS de 76,7, mientras que el caso comparado obtuvo 70,0. Esta diferencia nos permitió justificar que la metáfora del "equipo de 6" funcionaba mejor porque estaba más directamente asociada a la tarea de elegir ingredientes. El análisis A/B reforzó la idea de que la innovación visual no debe competir con la claridad del flujo.

También aprendí a reconocer limitaciones en nuestro propio trabajo. El proyecto PogoRamen todavía necesitaría más pruebas con usuarios reales, más atención a accesibilidad móvil, revisión sistemática de contraste, botones de volver más claros y ayuda contextual durante la personalización. Esta autocrítica es parte del aprendizaje: un diseño no termina cuando el mockup se ve bien, sino cuando se comprueba que personas distintas pueden usarlo con eficacia, eficiencia y satisfacción.

Otra aportación importante ha sido la documentación del proceso. Al principio puede parecer una parte secundaria, pero en UX documentar bien es casi tan importante como diseñar, porque permite que otra persona entienda de dónde viene cada decisión. En el repositorio se recogen pasos, imágenes, plantillas, enlaces y conclusiones, lo que facilita reconstruir el razonamiento seguido. Esta práctica me ha ayudado a expresar mejor las decisiones de diseño, a distinguir entre evidencia y opinión y a preparar entregables más defendibles. También me ha hecho ver que un buen caso de estudio no debe limitarse a mostrar resultados finales, sino explicar el camino: problema, investigación, ideación, propuesta, evaluación y mejoras. Esta forma de comunicar será útil en proyectos futuros porque acerca el trabajo académico a una forma más profesional de presentar UX.

Mi autoevaluación final es que he adquirido una base sólida para abordar problemas de UI/UX con criterio. He aprendido a investigar, comparar, definir usuarios, mapear recorridos, ordenar información, diseñar componentes, crear prototipos y evaluar resultados. Mi mayor avance ha sido entender que el diseño de interfaces no consiste solo en hacer pantallas atractivas, sino en construir decisiones defendibles. La calidad de una propuesta depende de su relación con necesidades reales, evidencias recogidas y criterios de usabilidad. Todavía debo mejorar en investigación con usuarios reales, accesibilidad avanzada y documentación más sintética, pero considero que el proyecto demuestra una evolución clara desde una idea creativa inicial hacia un proceso de diseño más profesional y centrado en personas.

## Parte II: Caso de estudio ECO MERCADO UGR

### 1. Objetivo y alcance

La segunda parte aplica la metodología de UX a un caso real: diseñar una propuesta de valor para el ECO MERCADO UGR. El objetivo no es crear una tienda online completa, sino analizar referentes existentes de mercados ecológicos y traducir sus aprendizajes en una propuesta web o app para la Universidad de Granada.

Se toma como referencia principal la web de [Nuestras Huertas](https://www.nuestrashuertas.com/), una iniciativa de fruta y verdura ecológica de la Sierra Norte de Madrid que comunica producción propia, productores, cestas semanales, tienda y mercados. También se revisa la información oficial de Impronta Granada sobre el [evento inaugural del Ecomercado UGR](https://improntagranada.es/evento/jornada-inaugural-del-ecomercado-ugr/) y la noticia de la [edición del 28 de mayo de 2026](https://improntagranada.es/novedades/el-ecomercado-ugr-celebra-una-nueva-edicion-el-28-de-mayo-con-productores-locales-comercio-justo-y-actividades-abiertas/). La web de Mercat Pages indicada en el enunciado se intentó consultar durante la revisión, pero devolvió acceso bloqueado desde el entorno de consulta; por eso no se usa como fuente principal.

### 2. Contexto del ECO MERCADO UGR

El Ecomercado UGR se plantea como una iniciativa vinculada a producción agroecológica local, consumo responsable, comercio justo, comunidad universitaria y ciudadanía. Según la información de Impronta Granada, la jornada inaugural se celebró el 26 de marzo de 2026 en los Paseíllos Universitarios del Campus Fuentenueva, con horario de mercado de 9:30 a 14:00 y una programación complementaria de 10:00 a 13:00. La propuesta se impulsa junto a la Red Agroecológica de Granada y se alinea con Impronta Granada y Granada Tierra Viva.

La edición del 28 de mayo de 2026 refuerza el carácter recurrente del mercado. La noticia indica que se trata de un espacio mensual de encuentro entre producción agroecológica, comercio justo, comunidad universitaria y ciudadanía. También enumera participantes como Greenpeace, Oxfam Intermón, Cooperativa Valle y Vega, Aviguardal, Somos Vega Somos Tierra, Las Huertas de Paula, La Zarzamora, Como de Graná, Horno María Diezma, AlKhadra y otros agentes locales. Esta variedad demuestra que el producto digital debe resolver algo más que una agenda: debe ayudar a entender quién participa, qué ofrece cada entidad, cuándo ocurre, dónde está cada puesto y cómo puede prepararse la visita.

### 3. Usuarios objetivo

Se identifican cuatro perfiles principales:

| Perfil | Necesidad principal | Riesgo de fricción |
| --- | --- | --- |
| Estudiante UGR | Comer mejor, descubrir productos locales y aprovechar el paso por el campus | No saber cuándo está el mercado o qué productos encontrará |
| PAS/PDI | Comprar productos de proximidad durante la jornada laboral | Falta de información rápida sobre horario, ubicación y productores |
| Ciudadanía de Granada | Participar en una iniciativa abierta, sostenible y local | No identificar si el mercado está abierto a personas externas a la UGR |
| Productores/as y entidades | Visibilidad, confianza y contacto con nuevos consumidores | No disponer de ficha clara, ubicación del puesto o propuesta de valor |

La hipótesis de diseño es que una web/app ligera, móvil primero y centrada en la visita al mercado aumentaría la asistencia, reduciría dudas y haría más visible el impacto territorial del proyecto.

### 4. Análisis del referente: Nuestras Huertas

Nuestras Huertas comunica con claridad su propuesta: fruta y verdura ecológica en Madrid directa a casa, producción propia en Bustarviejo, productores asociados y cestas semanales. La web presenta navegación hacia "La Huerta", "Nosotros y Productores", "Cómo comprar", "Tienda", "Mercados", "Blog" y "Contacto". Desde UX, esto es positivo porque cubre las preguntas básicas del usuario: quiénes son, qué venden, cómo comprar y dónde encontrarlos.

Entre sus fortalezas destacan:

- Propuesta de valor clara: producto ecológico, libre de pesticidas y entregado con regularidad.
- Transparencia sobre origen: explica la huerta propia y el trabajo con productores.
- Conversión directa: la tienda y la suscripción a cestas son accesos visibles.
- Información de mercados: incluye ubicaciones y horarios de puntos físicos.
- Confianza social: muestra reseñas de clientes y presencia en redes.

También se detectan oportunidades de mejora:

- La página inicial acumula mucha información y puede obligar a desplazamiento prolongado.
- Los mercados aparecen como bloques informativos, pero no como una experiencia interactiva con mapa, filtros o recordatorio.
- La jerarquía de llamadas a la acción podría diferenciar mejor entre comprar online, visitar mercado y conocer productores.
- La información de accesibilidad está enlazada al pie, pero no se aprecia una estrategia visible de accesibilidad durante el recorrido.
- Para móvil, sería útil priorizar acciones rápidas: "ver próximo mercado", "cómo llegar", "qué habrá esta semana" y "guardar recordatorio".

La conclusión principal es que Nuestras Huertas resuelve bien la confianza y la conversión, pero el Ecomercado UGR necesita priorizar la planificación de visita, la visibilidad de participantes y el sentido comunitario.

### 5. Insights para ECO MERCADO UGR

1. **El usuario necesita saber si el mercado ocurre hoy o cuándo será el próximo.**  
   La información temporal debe aparecer en el primer bloque: fecha, horario, lugar y estado.

2. **La ubicación debe ser accionable.**  
   No basta con decir "Paseíllos Universitarios". La propuesta debe incluir mapa, acceso a Google Maps, puntos de transporte y referencia dentro del campus.

3. **Los productores son parte central de la experiencia.**  
   Cada puesto debería tener ficha mínima: nombre, categoría, origen, productos, certificación o enfoque, y contacto.

4. **La ciudadanía externa debe sentirse invitada.**  
   La web debe aclarar que el mercado no es solo para estudiantes, sino un espacio abierto de universidad y territorio.

5. **La sostenibilidad debe traducirse en acciones concretas.**  
   El discurso de consumo responsable debe conectarse con decisiones: traer bolsa, comprar de temporada, conversar con productores, asistir a talleres o participar en actividades.

6. **La interfaz debe ser móvil primero.**  
   El contexto de uso probable es en movimiento: antes de salir de casa, caminando por el campus o durante una pausa entre clases.

### 6. Propuesta de valor

**ECO MERCADO UGR digital** sería una web/app ligera para descubrir, planificar y vivir el mercado ecológico universitario. Su objetivo sería convertir la información dispersa en una experiencia clara: cuándo ir, dónde está, qué productores participan, qué productos hay, qué actividades se celebran y cómo seguir vinculado al proyecto.

Propuesta de valor:

> "Consulta el próximo Ecomercado UGR, descubre productores locales, prepara tu visita y participa en una comunidad universitaria conectada con la agroecología y el consumo responsable."

### 7. Arquitectura de información propuesta

| Sección | Contenido | Objetivo UX |
| --- | --- | --- |
| Próximo mercado | Fecha, hora, ubicación, CTA de cómo llegar y guardar recordatorio | Resolver la primera duda en menos de 10 segundos |
| Productores | Fichas filtrables por categoría: fruta, hortalizas, pan, huevos, comercio justo, talleres | Dar visibilidad y preparar la compra |
| Mapa de puestos | Plano simple de Paseíllos con numeración | Reducir desorientación durante la visita |
| Actividades | Talleres, coloquios, programación y horarios | Mostrar que el mercado también es aprendizaje |
| Guía responsable | Consejos: traer bolsa, comprar temporada, preguntar origen, evitar desperdicio | Traducir sostenibilidad a acciones |
| Comunidad | Newsletter, redes, contacto y formulario para productores | Mantener continuidad mensual |

### 8. Requisitos funcionales del MVP

- Ver fecha, horario y ubicación del próximo mercado.
- Consultar entidades participantes.
- Filtrar productores por tipo de producto.
- Abrir indicaciones de llegada.
- Guardar recordatorio en calendario.
- Consultar actividades del día.
- Ver recomendaciones de compra responsable.
- Acceder a contacto o participación.

### 9. Criterios de diseño y usabilidad

La propuesta debe seguir principios de Nielsen y buenas prácticas de accesibilidad:

- **Visibilidad del estado del sistema:** indicar si el próximo mercado está confirmado, próximo o finalizado.
- **Correspondencia con el mundo real:** usar lenguaje cotidiano, no administrativo.
- **Control del usuario:** acceso rápido a volver, filtros claros y navegación simple.
- **Consistencia:** mismas tarjetas y etiquetas para productores.
- **Prevención de errores:** fechas completas, mapas claros y enlaces revisados.
- **Reconocimiento mejor que recuerdo:** categorías visibles con iconos y texto.
- **Accesibilidad:** contraste suficiente, botones grandes, tipografía legible, estados de foco y contenido comprensible sin depender solo del color.

### 10. Boceto de interfaz

Se propone una pantalla inicial móvil primero con cuatro bloques:

1. Cabecera con nombre "ECO MERCADO UGR", fecha del próximo evento y CTA "Cómo llegar".
2. Tarjetas rápidas: "Productores", "Mapa", "Actividades", "Recordatorio".
3. Lista filtrable de puestos con categoría, origen y producto destacado.
4. Bloque de guía responsable y participación.

El mockup HTML está incluido en [`mockups/ecomercado-ugr-web.html`](mockups/ecomercado-ugr-web.html). No pretende ser un producto final, sino un boceto funcional que muestra jerarquía, contenido y flujo principal.

### 11. Evaluación esperada

Para evaluar la propuesta se plantearía una prueba moderada con 5 usuarios:

| Tarea | Métrica |
| --- | --- |
| Encontrar fecha y horario del próximo mercado | Tiempo y éxito de comprensión |
| Localizar un productor de hortalizas | Éxito, pasos y errores |
| Saber cómo llegar al mercado | Tiempo hasta CTA correcto |
| Identificar una actividad de sensibilización | Comprensión de programación |
| Explicar qué aporta el Ecomercado UGR | Claridad de propuesta de valor |

Se complementaría con SUS, revisión heurística y checklist WCAG básica. El objetivo sería alcanzar una puntuación SUS superior a 75 y detectar problemas de comprensión antes de implementar una versión pública.

### 12. Relación con las prácticas

El caso ECO MERCADO UGR conecta directamente con lo aprendido en PogoRamen. En ambos casos existe una experiencia presencial apoyada por una interfaz digital. En PogoRamen, la interfaz guía la creación de un plato; en ECO MERCADO UGR, la interfaz guía una visita a un mercado. En los dos proyectos, la clave está en no confundir identidad visual con experiencia de usuario. La temática de PogoRamen debía ayudar a elegir ingredientes; la sostenibilidad del Ecomercado debe ayudar a comprar mejor, descubrir productores y participar.

Lo que aplicaría de las prácticas a este caso:

- Investigación inicial para entender perfiles de usuarios.
- Análisis competitivo de referentes.
- Personas y journey map para estudiar momentos antes, durante y después de la visita.
- Sitemap y labelling para evitar lenguaje institucional excesivo.
- Wireframes móviles antes de diseño visual.
- Evaluación heurística y pruebas con usuarios.
- Sistema de componentes para tarjetas, filtros, CTAs y estados del mercado.

Lo que faltó hacer con más profundidad en las prácticas y sería importante aquí:

- Validación con usuarios reales, no solo ficticios.
- Revisión accesible más estricta.
- Diseño más detallado para móvil.
- Métricas de impacto: asistencia, repetición, clics en productores, guardado de recordatorios.
- Contenido mantenible, porque un mercado mensual necesita actualización constante.

### 13. Conclusión

El caso ECO MERCADO UGR demuestra que el diseño UX es especialmente útil cuando una iniciativa real tiene valor social, pero necesita hacerlo comprensible y accionable. La información existente comunica bien la importancia del mercado, pero una interfaz específica podría mejorar la asistencia, la orientación y la relación entre universidad, ciudadanía y productores.

La propuesta final se centra en claridad, movilidad y confianza: mostrar el próximo mercado, explicar quién participa, facilitar la llegada y convertir la sostenibilidad en acciones simples. Esta solución aplica lo aprendido durante el curso y corrige algunas limitaciones detectadas en el propio proyecto PogoRamen: más foco en móvil, más accesibilidad, contenido más directo y evaluación desde tareas reales.

## Fuentes consultadas

- [Nuestras Huertas](https://www.nuestrashuertas.com/), consultado el 14 de junio de 2026.
- [Jornada inaugural del Ecomercado UGR - Impronta Granada](https://improntagranada.es/evento/jornada-inaugural-del-ecomercado-ugr/), consultado el 14 de junio de 2026.
- [El Ecomercado UGR celebra una nueva edición el 28 de mayo - Impronta Granada](https://improntagranada.es/novedades/el-ecomercado-ugr-celebra-una-nueva-edicion-el-28-de-mayo-con-productores-locales-comercio-justo-y-actividades-abiertas/), consultado el 14 de junio de 2026.
- Materiales propios del repositorio [`Mercenari23/UX_CaseStudy`](https://github.com/Mercenari23/UX_CaseStudy.git).
