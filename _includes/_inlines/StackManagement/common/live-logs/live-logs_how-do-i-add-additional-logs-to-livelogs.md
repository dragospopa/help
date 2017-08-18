<!-- post: -->


## How do I add additional logs to LiveLogs?

By default LiveLogs will look for logs in the following paths: 

*   /var/log/containers/*.log
*   /var/log/containers/**/*.log
*   /tmp/web_server_bluepill.log
*   $STACK_BASE/shared/log/*.log

You can add your own custom paths to this by using a [manifest files](/building-your-stack/building-your-manifest-file) and adding the key `***/configuration/custom_log_files`. 

See the example below to add custom log files to all Rails servers: 



{%include _inlines/StackManagement/common/live-logs/code_live-logs_how-do-i-add-additional-logs-to-livelogs-od.md %}




You can also have multiple custom log files defined for different server roles; for instance see the example below to add custom log files to all Docker servers with different custom log files for all MySQL servers (on the same stack)



{%include _inlines/StackManagement/common/live-logs/code_live-logs_how-do-i-add-additional-logs-to-livelogs-od.md %}






