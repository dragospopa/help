<!-- layout:code post: proc-files_how-to-run-background-processes -->

```

worker: rake resque:work QUEUE=*
scheduler: rake resque:scheduler

```