docker build -t my_project .
docker run -p 8888:8888 my_project
//
docker run my_project python train.py