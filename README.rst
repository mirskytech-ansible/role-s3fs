Description
----------------------

Instals fuse over amazon allowing to mount a bucket for access as a directory

Required variables
----------------------

s3fs_aws_key: please_specify_in_playbook
s3fs_mounts:
    - { mount: <mount directory>, bucket: <bucket name> }
    - { mount: /mnt/s3, bucket: mybackupbucket }
    
References
----------------------

- https://github.com/s3fs-fuse/s3fs-fuse/wiki/Installation-Notes