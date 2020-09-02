pip install flask
pip install flask_restful
pip freeze > requirements.txt
#pip3 freeze > requirements.txt
#pip install docker
docker build -t flaskytd .
#               flaskytd is the name of docker image I given, you can give any name you want.  

docker run -it -p 5000:5000 flaskytd




docker build -t flaskytd .     
#docker build .     
#           is used to build docker image and to give name and tag 
#                                                                  -t
#                                                                  is used
# when image is build then 
                        docker run ImageName 
                        is used to run docker image





for more watchthis videos:-
                        https://www.youtube.com/watch?v=awd81AfC-KA
                        https://www.youtube.com/watch?v=LQjaJINkQXY&list=PLhW3qG5bs-L99pQsZ74f-LC-tOEsBp2rK&index=13&t=0s
                        https://www.youtube.com/watch?v=hD_q1KSB3Ho
                        https://github.com/pundrikmishra/Docker