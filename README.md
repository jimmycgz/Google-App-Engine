# Google-App-Engine

## Built below Demo website by Google App Engine 

Has 3 services up running, two of them share the workload and the 3rd one is idle. Open by browser and prcess <F5> multiple times to see the two versions.

https://app-eng-2.appspot.com/


## Steps in GCP CLI

TUTORIALDIR=src/app-eng-2/php_gae_quickstart-2018-09-03-19-11

git clone https://github.com/GoogleCloudPlatform/appengine-php-guestbook.git $TUTORIALDIR

cd $TUTORIALDIR

git checkout phase3-staticfiles

gcloud app deploy app.yaml --project app-eng-2

gcloud app browse --project=app-eng-2

