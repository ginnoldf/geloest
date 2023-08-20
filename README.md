docker build -t geloest
docker run -p "80:80" geloest

gcloud builds submit --tag us-west2-docker.pkg.dev/telimektar/repo/geloest:alpha .