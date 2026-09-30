# Historias de usuario individuales

**Nombre:** Sergio Martinez Marin

**Usuario de GitHub:** Sergiotechx

---

## Mis historias de usuario

> Entre 5 y 7 historias en formato "como [rol] quiero [acción] para [beneficio]", pensadas desde distintos roles o necesidades del producto que el equipo está diseñando. Si escribes menos de 7, borra las líneas que no uses (mínimo 5).

1. Como **emisor** quiero emitir un certificado a un titular con sus datos (nombre, curso, fecha) como una credencial NFT intransferible para que quede registrado de forma inalterable y no pueda ser falsificado ni traspasado.
2. Como **verificador** quiero escanear un código QR o abrir un enlace del documento para confirmar en segundos si es auténtico, sin crear una cuenta ni tener billetera cripto.
3. Como **titular** quiero ver mi certificado y compartirlo con un enlace o QR para demostrar mi acreditación a un tercero sin pedirle copias a la institución.
4. Como **emisor** quiero revocar un certificado emitido por error para que la verificación lo muestre como no vigente.
5. Como **administrador de Qedify** quiero habilitar y controlar qué instituciones pueden emitir documentos para que solo emisores legítimos generen registros confiables.
6. Como **titular** quiero que mi certificado siga siendo verificable aunque la institución cambie de sistema o desaparezca para no depender de ella cada vez que necesite demostrarlo.
7. Como **titular** quiero copiar mi credencial a mi propia billetera Stellar, sabiendo que el original sigue custodiado en Qedify, para tener control directo sobre ella sin perder el respaldo de la plataforma.

## La más importante y por qué

> Organiza las historias de mayor a menor importancia: en la primera fila va la más importante. En cada fila indica el número de la historia y por qué la ubicaste en esa posición. Si usaste menos de 7 historias, borra las filas que sobren.

| Orden de importancia | Historia # | Por qué |
| :---: | :---: | --- |
| 1 (la más importante) | 1 | Sin emisión no existe ningún documento que verificar; es el punto de partida de todo el flujo y donde se ancla la huella en la blockchain. |
| 2 | 2 | Es el valor central para quien confía en el documento: pasar de días de espera a segundos, sin cuenta ni billetera. Es lo que ataca directamente la fricción 1 del Problem Brief. |
| 3 | 5 | Un registro inalterable solo vale si quien emite es legítimo; si cualquiera puede emitir, la plataforma certificaría documentos falsos como auténticos. |
| 4 | 3 | El titular es quien lleva el documento ante terceros; que pueda verlo y compartirlo con un toque cierra el ciclo emisor → titular → verificador. |
| 5 | 6 | Es la promesa diferencial frente a los QR actuales, pero en el MVP se apoya en las historias anteriores y su alcance completo (por ejemplo, el respaldo del contenido) puede madurar después. |
| 6 | 4 | Los errores de emisión ocurren y hay que poder corregirlos, pero el producto ya entrega valor sin revocación en una primera versión. |
| 7 (la menos importante) | 7 | Da autonomía al titular y refuerza la propiedad de la credencial, pero el flujo emisor → titular → verificador funciona sin ella porque el original siempre queda custodiado en Qedify. |
