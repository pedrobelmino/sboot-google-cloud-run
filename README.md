# Executar comandos para build e deploy
```bash
gcloud builds submit --tag gcr.io/{NOME_DO_WORKSPACE_GOOGLE}/helloworld
gcloud run deploy --image gcr.io/{NOME_DO_WORKSPACE_GOOGLE}/helloworld --platform managed
```
