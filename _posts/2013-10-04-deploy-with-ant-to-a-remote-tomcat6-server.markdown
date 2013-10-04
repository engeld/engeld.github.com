---
layout: post
title: "Deploy with Ant to a remote Tomcat 6 server"
---
There are just two small steps required to enable remote tomcat-tasks in ant:

1. copy the **catalina-ant.jar** from the `$CATALINA_HOME/lib` into `$ANT_HOME/lib`
1. adjust the **build.xml**

The first step is pretty much self-explanatory but the second step requires a little more knowledge of tomcat. Fortunately these adjustment of the build.xml will always be the same so once they’re done you can basically just copy&paste the tasks into any other build.xml

{% gist engeld/4509224 %}
