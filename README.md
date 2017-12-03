# dockerManagement

[![Video](http://img.youtube.com/vi/M6IUKP4L1Kg/0.jpg)](http://www.youtube.com/watch?v=M6IUKP4L1Kg)

# Summary
Available API endpoints:
#####GET /containers                     
>List all containers
#####GET /containers?state=running      
>List running containers (only)
#####GET /containers/<id>                
>Inspect a specific container
#####GET /containers/<id>/logs           
>Dump specific container logs
#####GET /images                         
>List all images
#####POST /images                        
>Create a new image
#####POST /containers                    
>Create a new container
#####PATCH /containers/<id>              
>Change a container's state
#####PATCH /images/<id>                  
>Change a specific image's attributes
#####DELETE /containers/<id>             
>Delete a specific container
#####DELETE /containers                  
>Delete all containers (including running)
#####DELETE /images/<id>                 
>Delete a specific image
#####DELETE /images                      
>Delete all images

