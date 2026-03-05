# Automatic Job Vacancy Recommender (n8n)

## Qué hace
Workflow diario en n8n que:
1) Toma usuarios activos
2) Divide en batches
3) Lee skills del perfil
4) Calcula top 5 vacantes con score + explicación
5) Inserta resultados en job_matches
6) Guarda ranking diario

## Cómo importarlo en n8n
1) n8n → Workflows → Import
2) Selecciona el archivo:
   `n8n/workflows/automatic-job-vacancy-recommender.json`

## Notas
- Credenciales de base de datos NO van en GitHub.
- Este repo solo guarda el workflow exportado y documentación.