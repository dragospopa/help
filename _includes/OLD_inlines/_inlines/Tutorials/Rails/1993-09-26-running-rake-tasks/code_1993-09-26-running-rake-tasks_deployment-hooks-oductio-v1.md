

```
production:
  after_rails:
    - source: /.cloud66/scripts/rake_task.sh
      destination: /tmp/rake_task.sh
      target: rails
      execute: true
      run_on: all_servers
      apply_during: all
      sudo: true
```