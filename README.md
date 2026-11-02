# ADSBlockVM — Lista propia

Lista de bloqueo de anuncios, rastreadores y malware armada con lo que **ADSBlockVM** bloquea de verdad en una red de casa, con las reglas de su dueño.

- Se actualiza sola **cada 3 días** y solo crece: lo que ya entró se queda y se agregan los dominios nuevos.
- Trae **excepciones** (`@@`): bancos y servicios que nunca deben bloquearse.
- No lleva nada personal: solo bloqueos de listas públicas y de reglas propias (nunca horarios, controles parentales ni la navegación de la casa).

## Cómo usarla

Dirección de la lista (formato AdGuard, también la entienden Pi-hole y AdGuard Home):

```
https://raw.githubusercontent.com/VicCodeM/ADSBlockVM-Lista/main/adsblockvm.txt
```

- **AdGuard Home:** Filtros → Listas de bloqueo DNS → Agregar lista → Agregar una lista personalizada.
- **Pi-hole:** Adlists → Address.
- **ADSBlockVM:** Filtros → Listas → Agregar.

Creado por Ing. Victor Maldonado - VMSofts
