<!--  usedin: [ _legacy_docker/AddOns/add-ins-jobs-v1.md, _maestro/AddOns/add-ins-jobs-v1.md, _node/addons/add-ins-jobs-v1.md, _rails/AddOns/add-ins-jobs-v1.md] -->


### Pass parameters to job

Since job is using positional parameters pass you arguments in order, eg: if you pass `arg1` `arg2`, `$1` would contain `arg1` and `$2` would contain `arg2`

You can also quote your argument if there is a space in the value.



{%include _inlines/AddOns/common/add-ins-jobs/code_add-ins-jobs_pass-parameters-to-job-bcommandcp-v1.md  product = include.product %}


