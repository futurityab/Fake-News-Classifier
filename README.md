# Fake-News-Classifier

Used to play around with fake news detection, adding sentiment analysis and possible some other if time allows. 


Datasets at https://www.kaggle.com/c/fake-news/notebooks

Running this in a docker container is probably the quickest way to get going, would be something like this (in a secured environment);

docker run -it --rm -p 8888:8888 -e NB_UID=501  -v /<Your path to this dir>/:/home/jovyan/work jupyter/datascience-notebook start.sh jupyter lab --ip=0.0.0.0 --LabApp.token='' --allow-root
