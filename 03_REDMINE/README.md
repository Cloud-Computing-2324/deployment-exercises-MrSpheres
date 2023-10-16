#Redmine

Opdracht 3 op Toledo. Als je gebruik maakt van Helm, zet je values-file in deze map, en je commando hieronder. Maak je gebruik van klassieke deployments, zet dan je bestanden in deze map.

$ helm repo add azure-marketplace https://marketplace.azurecr.io/helm/v1/repo
$ helm install -f values.yaml my-release-redmine azure-marketplace/redmine