# Problem Brief

## Decisión del problema

### Problema elegido

> El problema ganador en una frase, sin mencionar blockchain, y quién lo propuso.

Verificar si una acreditación o certificado que una persona presenta es real y no ha sido alterado es lento, manual y distinto para cada entidad emisora. Propuesto por Sergio Martinez Marin (único integrante del equipo).

### Por qué elegimos este

> Qué inclinó al equipo por este problema frente a los demás, según los criterios de la Sesión 1.

Al ser un equipo de una sola persona, este es el único problema evaluado, y se decidió avanzar con él porque cumple con claridad uno de los criterios de la Sesión 1: hay múltiples partes que no confían entre sí (entidades emisoras, empresas verificadoras y titulares) que necesitan compartir un mismo registro de verdad, y además se busca eliminar la dependencia de un intermediario (la entidad emisora) que hoy concentra la confianza sobre la validez del documento.

### Propuestas descartadas

> Cada propuesta considerada, quién la propuso y el motivo del descarte.

No aplica: al ser un equipo individual, no se evaluaron ni descartaron propuestas alternativas de otros integrantes.

### Cómo tomamos la decisión

> Cómo llegó el equipo al acuerdo: votación, consenso tras debate u otro.

Decisión individual, sin necesidad de votación o consenso con otros integrantes, al ser el único miembro del equipo.

---

## Problem Brief

### Encabezado

> Nombre del proyecto y una frase que describa el problema. Extensión: breve.

**Qedify** — Verificar si una acreditación o certificado que una persona presenta es real y no ha sido alterado es lento, manual y distinto para cada entidad emisora.

### Equipo y roles

> Integrantes con su usuario de GitHub, rol asumido por cada persona, responsable de las entregas y canal de coordinación interna. Extensión: breve.

- **Sergio Martinez Marin** (GitHub: sergiotechx) — único integrante del equipo. Asume todos los roles: investigación del problema, diseño de la propuesta y responsable de las entregas. Al ser un equipo individual, no hay canal de coordinación interna adicional.

### Problema y evidencia

> Enunciado del problema en una frase, sin mencionar blockchain. Contexto, frecuencia y alcance. Evidencia mínima de que el problema existe: observación directa, experiencia propia, conversaciones o fuentes consultadas, con enlace o cita cuando aplique. Extensión: 150–300 palabras.

Verificar si una acreditación o certificado presentado por una persona es real y no ha sido alterado es un proceso lento, manual y distinto según la entidad emisora. Este problema se vive en Colombia y, en general, en Latinoamérica, cada vez que una empresa, universidad o entidad necesita confirmar un título, diplomado o certificado de asistencia mostrado por un candidato o solicitante, ya sea en procesos de selección laboral, admisión académica o trámites administrativos. Ocurre con alta frecuencia, prácticamente en cada contratación o proceso de admisión, y afecta tanto a organizaciones grandes con procesos formales de verificación como a pequeñas empresas sin recursos para hacerlo de forma rigurosa.

La evidencia surge de la observación directa del proceso actual: la mayoría de instituciones no ofrece un mecanismo estandarizado de verificación; algunas han empezado a incorporar códigos QR en sus certificados para facilitar la validación, pero esto no es una práctica generalizada ni interoperable entre entidades. Esto obliga a que la verificación se resuelva caso por caso, por correo, llamada telefónica o portales independientes de cada institución, lo que abre espacio tanto a errores como a la presentación de documentos falsificados que no pasan por ningún control real.

### Usuario y actores

> Quién sufre el problema y qué necesita resolver. Cómo lo resuelve hoy y qué le cuesta en dinero, tiempo o esfuerzo. Demás actores que intervienen en el flujo, con el papel que cumple cada uno. Extensión: 150–300 palabras.

Quienes más sufren el problema son las empresas, instituciones educativas y demás entidades verificadoras, que necesitan confirmar de forma ágil y confiable las acreditaciones que una persona presenta en procesos de selección, admisión o contratación. También lo sufre el titular del documento, quien debe conservar copias físicas o digitales de cada certificado y volver a tramitarlas ante la entidad emisora si las pierde o si necesita reenviarlas a un nuevo verificador.

Hoy la verificación se resuelve de manera manual y distinta para cada entidad: llamadas, correos electrónicos o consultas en portales propios sin un estándar común. Algunas instituciones ofrecen código QR para agilizar el proceso, pero no es una práctica extendida. Esto le cuesta tiempo al verificador, que debe contactar directamente a cada entidad emisora, y le cuesta esfuerzo y dinero al titular, que depende de que la institución siga existiendo y mantenga sus registros disponibles para poder demostrar la validez de su documento.

Los actores del flujo son: el **Emisor** (institución educativa, empresa u organizador de eventos que expide el documento), el **Titular** (persona que recibe el documento y lo presenta ante terceros) y el **Verificador** (empresa o entidad que necesita confirmar la autenticidad del documento presentado).

### Flujo actual de valor

> Recorrido paso a paso de cómo se mueve hoy el dinero, la información o el activo, desde el origen hasta el destino. Diagrama o secuencia numerada, con los intermediarios explícitos. Señalar si algún paso responde a una obligación normativa. Extensión: 150–300 palabras.

1. La entidad emisora (institución educativa, empresa o entidad certificadora) expide el certificado o diploma, generalmente en formato físico o PDF, tras culminar un curso, diplomado o proceso de certificación.
2. El titular recibe el documento y lo guarda como respaldo personal, en papel o en archivos digitales dispersos (correo, computador, nube personal).
3. Cuando el titular necesita demostrar su acreditación (por ejemplo, en un proceso de selección laboral), envía una copia del documento al verificador (empresa, universidad u otra entidad).
4. El verificador, para confirmar que el documento es auténtico, contacta directamente a la entidad emisora original, mediante correo, llamada telefónica o un portal propio de esa institución (cuando existe).
5. La entidad emisora responde confirmando o negando la validez del documento, en un tiempo que puede tardar días.
6. Si la entidad emisora ya no existe, cambió de sistema o no responde, el verificador queda sin forma confiable de confirmar la autenticidad, y el titular sin manera de demostrarla.

En algunos sectores regulados (por ejemplo, validación de títulos profesionales ante ciertas entidades del Estado), este paso de verificación responde además a una obligación normativa, no solo a una buena práctica interna del verificador.

### Fricciones identificadas

> Puntos concretos donde el flujo falla, se encarece o se demora. Cada fricción indica en qué paso ocurre, qué la causa y a quién afecta. Extensión: 150–300 palabras.

- **Fricción 1 (paso 4):** el verificador debe contactar individualmente a cada entidad emisora, sin un canal ni formato estándar. Esto ocurre porque no existe un mecanismo unificado de verificación entre instituciones, y afecta principalmente al verificador, que pierde tiempo repitiendo este proceso por cada documento y cada entidad distinta.
- **Fricción 2 (paso 5):** la respuesta de la entidad emisora puede tardar días o no llegar, porque depende de la disponibilidad administrativa de esa institución. Esto afecta tanto al verificador, que retrasa su proceso de decisión (por ejemplo, una contratación), como al titular, que puede perder oportunidades por la demora.
- **Fricción 3 (paso 6):** si la entidad emisora desaparece, cambia de sistema o simplemente no lleva un archivo histórico accesible, el documento queda sin forma de validarse, afectando directamente al titular, que pierde la posibilidad de demostrar una acreditación legítima.
- **Fricción 4 (transversal):** al no existir un control uniforme, un tercero puede presentar un certificado falsificado o alterado sin que el verificador tenga una manera rápida y confiable de detectarlo, lo que genera riesgo tanto reputacional como legal para quien confía en ese documento.
- **Fricción 5 (paso 2):** el titular concentra el riesgo de conservar sus documentos dispersos y sin respaldo estandarizado, por lo que ante pérdida debe iniciar un trámite nuevo con la entidad emisora, con el costo de tiempo y a veces dinero que eso implica.

### Oportunidad e hipótesis

> Oportunidad priorizada entre las fricciones identificadas, con el motivo de la elección. Hipótesis inicial de por qué blockchain podría mejorar ese punto, expresada en términos de qué cambiaría para el usuario. Extensión: 150–300 palabras.

La oportunidad priorizada es la Fricción 1 y 3 combinadas: la falta de un mecanismo de verificación estandarizado e independiente de la disponibilidad continua de la entidad emisora. Se prioriza esta porque es la raíz de las demás fricciones: si existiera un registro único, verificable por cualquiera y que no dependiera de que la institución emisora siga operando o respondiendo, se resolverían de un solo golpe la lentitud de la verificación manual (Fricción 1), el riesgo de que el emisor desaparezca (Fricción 3) y gran parte del riesgo de falsificación (Fricción 4).

La hipótesis es que anclar cada documento emitido como una huella o token en una blockchain pública permitiría que cualquier verificador, sin necesidad de contactar a la entidad emisora ni crear una cuenta, confirme en segundos si el documento es auténtico y no ha sido alterado, simplemente escaneando un código QR o accediendo a un enlace. Para el titular, esto cambia que ya no dependa de que la institución exista o responda a tiempo: el documento sigue siendo verificable de forma permanente. Para el verificador, cambia un proceso de días por uno de segundos, sin intermediarios ni contacto directo con cada entidad distinta.

### Criterio de pertinencia

> Justificación de por qué el caso requiere un registro distribuido y no una base de datos tradicional o una integración entre sistemas existentes. Debe apoyarse en al menos uno de los criterios de la Sesión 1: varias partes que no confían entre sí necesitan compartir un mismo registro, el histórico no puede alterarse, o se elimina un intermediario que hoy concentra la confianza. Extensión: 150–300 palabras.

Este caso cumple con al menos dos de los criterios de la Sesión 1. Primero, hay múltiples partes que no confían entre sí de forma inherente: entidades emisoras (universidades, empresas, organizadores de eventos), titulares y verificadores externos no tienen una relación de confianza previa, y cada uno necesita poder consultar el mismo registro de verdad sin depender de la palabra de otro. Una base de datos tradicional resolvería esto solo si todas las entidades emisoras aceptaran centralizar sus registros en un sistema controlado por un tercero (la plataforma), lo cual reintroduce exactamente el problema que se busca resolver: un intermediario único que concentra la confianza y que, si desaparece o es comprometido, deja sin validez a todos los documentos.

Segundo, el histórico no puede alterarse: la razón de ser de un certificado es que su contenido (nombre, fecha, institución, logro) permanezca inmutable desde el momento de emisión. Una base de datos convencional permite ediciones, borrados o manipulación por parte de quien administra el sistema, incluso sin mala intención, mientras que un registro anclado en una blockchain pública ofrece una prueba independiente y verificable de que el documento no ha cambiado desde su emisión, sin depender de que se confíe en el operador de la base de datos. Esto es lo que permite que el documento siga siendo verificable aunque la institución emisora cambie de sistema o deje de operar.

### Supuestos y riesgos

> Dos o tres supuestos que tendrían que ser ciertos para que la hipótesis funcione, y qué podría invalidarla. Extensión: 150–300 palabras.

- **Supuesto 1:** las entidades emisoras (instituciones educativas, empresas, organizadores de eventos) están dispuestas a adoptar una plataforma nueva para emitir sus certificados, en lugar de sus procesos actuales en papel o PDF. Esto podría invalidarse si las entidades perciben más fricción en migrar (costo, curva de aprendizaje, cambio de proceso interno) que el beneficio que obtienen al ofrecer verificación instantánea a terceros.
- **Supuesto 2:** los verificadores (empresas, universidades u otras entidades) confían en un registro público en blockchain como prueba suficiente de autenticidad, sin necesitar todavía contactar directamente a la entidad emisora. Esto podría invalidarse si los verificadores, por cultura organizacional o requisitos legales internos, exigen igualmente una confirmación directa de la institución, sin importar que exista un registro verificable en blockchain.
- **Supuesto 3:** el volumen de instituciones que emiten certificados de cursos, diplomados y asistencia (el foco de la Fase 1) es suficientemente alto en Colombia y Latinoamérica como para sostener un negocio, y estas instituciones tienen relación cercana con al menos algunos verificadores externos que se beneficiarían de este cambio. Esto podría invalidarse si el mercado real es demasiado fragmentado o si las instituciones emisoras no perciben suficiente presión externa (de empleadores u otras entidades) para adoptar un nuevo estándar de verificación.
