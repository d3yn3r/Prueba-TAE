gcloud builds submit --tag gcr.io/trabajo-2-tae/dash-example  --project=trabajo-2-tae

gcloud run deploy --image gcr.io/trabajo-2-tae/dash-example --platform managed  --project=trabajo-2-tae --allow-unauthenticated