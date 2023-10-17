
Pull an image from Dockerfile
    docker image pull diamol/ch03-lab

Run the container interactively
    docker run -it --rm --name resolve diamol/ch03-lab

Update the text file
    echo xyz >> ch03.txt

Commit the changes
    docker container commit resolve

Run the updated docker image 
    docker container run -it sha256id