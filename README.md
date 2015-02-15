# jenkins_workshop
material for jenkins workshop

# Lets Install Jenkins on your computer
Step 1: Download Jenkins: http://jenkins-ci.org/

Step 2: start jenkins: 
java -jar jenkins.war

# Excercise 1: Hello World
echo Hello world!

# Excercise 2: Periodic Build
say hello world every minute! (cron expression for this is "* * * * *")

# Excercise 3: Am I online ?
create a jenkins job that checks if you are online every minute, and then disconnect the wifi.
(command to ping 3 times is for example "ping -c 3 host")

# Excercise 4: Choice Parameters
Create a job that passes or fails based on a choice in build parameter.

# Excercise 5: Send an Email
create a jenkins job that sends an email to yourself.

# Excercise 6: Create a job that triggers another job
create a job called "knock knock", which calls a another job that says "who's there?"

# Excercise 7: Smarter Flows
create a job that triggers a clone based on pushed items to this repo
if it succeeds, trigger job A, if it fails, trigger job B.

# Excercise 8: Naginator Plugin
create a job that fails permanently, and use the naginator plugin to have it try again in increasing variable time

# Excercise 9: Git Plugin
create a job that triggers a clone based on pushed items to this repo
