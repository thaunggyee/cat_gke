var

gcloud config set project $PROJECT
gcloud config set compute/zone $ZONE
gcloud config set container/cluster $CLUSTER

trigger

_CLOUDSDK_COMPUTE_ZONE --> us-central1-b
_CLOUDSDK_CONTAINER_CLUSTER --> gke-deploy-cluster
