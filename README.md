# jira-confluence
you can install jira and confluence with code
~~~~
$ docker-compose up -d
~~~~

after that

you can see crack jira and confluence 
/var/lib/Atlassian


when you get lincence key with server id 

crack jira
~~~~
$ java -jar atlassian-agent.jar -d -m [yourEmail] -n BAT -p jira -o http://[ServerIp-Or-Domain] -s [serverId]
~~~~




crack confluence
~~~~
$ java -jar atlassian-agent.jar -d -m [yourEmail] -n BAT -p conf -o http://[ServerIp-Or-Domain] -s [serverId]
~~~~


# Related Images

You may also like:

* [jira][https://hub.docker.com/r/atlassian/jira-software]: jira image in docker hub
* [confluence][https://hub.docker.com/r/atlassian/confluence-server]: confluence image in docker hub
