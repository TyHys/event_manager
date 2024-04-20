# Updated README: Replace the existing README with:

* Links to the closed issues, providing easy access to your work.  
    * [Unclear Registration Failure due to duplicate email #9](https://github.com/TyHys/event_manager/issues/9)  
    * [Example Name Correction #7](https://github.com/TyHys/event_manager/issues/7)  
    * ["ANONYMOUS" Is not valid for userroles #5](https://github.com/TyHys/event_manager/issues/5)  
    * [Update User Error #4](https://github.com/TyHys/event_manager/issues/4)  
    * [Registration Failure #1](https://github.com/TyHys/event_manager/issues/1)  
* Link to project image deployed to Dockerhub:   
    * [DockerHub](https://hub.docker.com/r/tewq01/wis_club_api)  
* A 2-3 paragraph reflection on what you learned from this assignment, focusing on both technical skills and collaborative processes. Reflect on the challenges you faced, the solutions you implemented, and the insights you gained. This reflection helps solidify your learning and provides valuable feedback for improving the assignment in the future:


>This assignment was definitely a big undertaking for me, since I've very little experience in APIs and the sort of troubleshooting that we were tasked with. That being said, I also feel like I learned a ton from going through the motions of learning what an application was intended to do and testing that functionality. Debugging each issue independently to try to determine how the flow of data works in the application was definitely a useful skill.  

>   The biggest thing I learned was to be really concentrate on the logging that was being put out of the application. Often times I would notice that something wasn’t right within the application (e.g. the register endpoint returned a 500 status), but I didn’t really even know where to begin. Looking at the logs and seeing where the failures returned information really helped to ground myself with where I should begin in looking to resolve the issue.  

>   Another big thing I learned through the course of this assignment was to pay close attention to the status of the back-end database that the program is attached to. Sometimes I would encounter what I thought to be an application issue, only to remember that I had deleted the ‘users’ table by running Pytest in the container. I also kept a close eye on the database while I was doing operations like registering and updating users to see that the changes were reflected in the database. This approach gave me a lot more comfort with knowing that things were working instead of just returning  a status code in the 200s.