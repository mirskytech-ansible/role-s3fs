Description
----------------------

Instals fuse over amazon allowing to mount a bucket for access as a directory

Required variables
----------------------

Please specify these in your playbook before using this role::


    s3fs_aws_key

    s3fs_mounts:
        - { mount: <mount directory>, bucket: <bucket name> }
        - { mount: /mnt/s3, bucket: mybackupbucket }
    
References
----------------------

- https://github.com/s3fs-fuse/s3fs-fuse/wiki/Installation-Notes