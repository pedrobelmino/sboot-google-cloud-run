# Executar comandos para build e deploy
```bash
gcloud builds submit --tag gcr.io/des-poc/helloworld
gcloud run deploy --image gcr.io/des-poc/helloworld --platform managed
```
