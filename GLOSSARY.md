# Glosario

Términos fijos de la traducción. La guía de estilo está en [STYLE.md](STYLE.md).

## Reglas

- **G-1** Si la serie tiene una traducción oficial al español (otro juego, el anime, un manual), los términos que comparte con este juego llevan el nombre oficial. Se toma solo el término; el registro es siempre el de esta traducción. Completar en el PLAN cuál es la fuente oficial, o borrar esta regla si no hay. [IVA]
- **G-2** Lo propio de este juego se decide aquí. Hasta que esté decidido, el término va a [PENDING.md](PENDING.md) con una propuesta. [IVA]
- **G-3** Un término de esta tabla se usa igual en todo el juego. `loc.py check` avisa cuando el original lo tiene y la traducción no (`glosario`). [Encargo §6]

## Cómo se arma

1. El terminólogo revisa los candidatos (los de la fuente oficial, si hay, y los términos de sistema del juego) y propone las filas: *oficial* si es el mismo término, o *por decidir* si significa otra cosa en este juego.
2. Las filas *oficial* entran a la tabla. Las *por decidir* van a [PENDING.md](PENDING.md) para que las decida el usuario.

## Términos

Por sección. *Oficial* (G-1) o *decidido* por el usuario (G-2), con fecha. La primera columna es el original en inglés; `loc.py` lee toda tabla cuya cabecera empiece por `| Inglés |`.

| Inglés | Español | Fuente | Nota |
|---|---|---|---|
