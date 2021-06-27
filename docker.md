docker container ls --all 
docker exec -it 1cb455259485 bash
docker cp wine.data 7cad29b0eddb:/home/jovyan/wine.data
docker run -v C:\Users\Vitaliy_Malievsky\Desktop\docker:/home/jovyan/ -p 8888:8888 jupyter/scipy-notebook:33add21fab64