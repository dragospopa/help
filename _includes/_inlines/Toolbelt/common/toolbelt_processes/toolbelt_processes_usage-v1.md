<!--  usedin: [ _legacy_docker/Toolbelt/toolbelt_processes-v1.md, _maestro/Toolbelt/toolbelt-processes-v1.md, _node/toolbelt/toolbelt-processes-v1.md, _rails/Toolbelt/toolbelt-processes-v1.md] -->


### Usage



{%include _inlines/Toolbelt/common/toolbelt_processes/code_toolbelt_processes_usage-cxprocesses-2-v1.md  product = include.product %}




Scales up/down <count> processes. If you specify [+X] or [-X] for the count, then that number of processes will be added/removed. Specifying a number without [ ] will act as an absolute value meaning that the resulting number of processes will be that number (it might scale up or down). Optionally provide the server to act only on that server.
