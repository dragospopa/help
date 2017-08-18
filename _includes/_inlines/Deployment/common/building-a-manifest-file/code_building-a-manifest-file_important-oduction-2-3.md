<!-- layout:code post: building-a-manifest-file_important -->

```

production:
    rails:
        server:
            unique_name: app
            vendor: aws
            key_name: Default
            region: us-east-1
            size: m3.medium
            root_disk_size: 100
            root_disk_type: ssd
            subnet_id: subnet-40000000
            availability_zone: us-east-1c

```