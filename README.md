# All-about-Jenkins
Install in Wiindows

step 1: check java version

step 2: Download jenkins.war file

step 3: cmd ->java -jar jenkins.war --httpPort=9191(what ever port we want)

step 4: ON browser http://localhost:9191

step 5: provide admin password


CI/CD PIPELINE:
CI-CD - Continuous Integration / continuous delivery or deployment
Developer commits code to github
Devops Enginer take the code from github and make sure code is running in every server / env like in any cloud env/server.
How code goes to cloud?
ans:Through CI ( code should be  running integrated way in every env ) like mac , windows , ubantu.
Docker Tool helps to create Virtualized container.

Required Tools :
1->Code should be running (Integrated way like code should be running same way in ubantu , mac , windows) in every env - Docker ( Virtualized container )

2->Github [where all my code present ]

3->AWS EC2 Instace [ Like a fake server by amazon cloud ]

4->jenkins [deliver code to ec2 - need to create a pipeline - jenkins ] 


