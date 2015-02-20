
##Description
push2syslog allows you to push custom logs to syslog

## Installation

\# git https://github.com/nabello/push2syslog.git

\# mv push2syslog /etc

\# cd /etc/push2syslog

\# cp push2syslog /etc/init.d

\# cd /etc/init.d/

\# chmod 755 push2syslog


Now you can use the push2syslog service by adding paths of logs you want to push to syslog in 
/etc/push2syslog/list-of-paths then do:

\# service push2syslog start
to start pushing those logs to syslog

\# service push2syslog stop
to stop pushing those logs to syslog

Note that if you don't know if push2syslog is running or not you can use
\# service push2syslog status


Author: nabello