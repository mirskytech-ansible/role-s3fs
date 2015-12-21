Description
-----------

Installs s3fs allowing you to mount an AWS S3 bucket for access as a directory

Role Variables
--------------

Specify the mount point, the bucket to be mounted and the key to be used as
follows:

    s3fs_mounts:
        - { mount: <mount point>, bucket: <bucket name>, key: "<access key id:secret access key>" }
        - { mount: /mnt/s3, bucket: mybackupbucket, key: "ALIAIORJQUJYV49V3RQ:13XqKwmeppogfeBnVXMr+lsdfdsLjNwk6JP+LFnyXf" }
    
References
----------

- https://github.com/s3fs-fuse/s3fs-fuse/wiki/Installation-Notes
