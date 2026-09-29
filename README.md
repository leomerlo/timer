# timer

Contador de 2 minutos estilo StandBy para un teléfono apaisado: los números están hechos con una grilla de puntos que fluye. Un solo `index.html`, sin build ni dependencias.

- Cada 30 s se encienden todos los puntos.
- El flujo va mutando entre algoritmos (ondas, humo, corriente, gotas, metaballs, estelas) con una transición gaussiana. El botón ✦ fija uno; `?algo=humo` lo fija por URL.

## Deploy en Vercel

Importá este repo en vercel.com (framework preset: **Other**), o desde la terminal:

```bash
npx vercel --prod
```
