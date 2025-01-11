# exam_prep
build image command :
      docker build -t my-image .
run container for this image command:
      docker run --name my-container -p 4000:5000 my-image
check container list:
      docker ps -a   //for all containers list
      docker ps      //for running continers list
