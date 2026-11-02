# PokéSurvivor · canal

Estado del canal de YouTube para [pokesurvivor.com](https://pokesurvivor.com): si hay directo
y cuál es el último vídeo. Lo actualiza solo `.github/workflows/live.yml` cada 5 minutos.

Los datos están en la rama [`live`](../../tree/live):

| Archivo | Qué es |
|---|---|
| `live.json` | `{ live, id, at }`: si el canal está en directo y en cuál |
| `video.json` | `{ id, title, at }`: el último vídeo normal (sin shorts ni directos) |
| `aviso.json` | `{ id, desde, hasta }`: aviso de vídeo nuevo (se cambia a mano) |
