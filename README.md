# 🩺 LabCAS Test Upload Data

This directory contains random data in a variety of files arranged in a hierarchy of directories in order to test the uploading of data into the [LabCAS backend server](https://github.com/EDRN/labcas-backend) using the [Amazon Simple Storage Service](https://aws.amazon.com/s3/) over [SSH Secure File Transfer Protocol](https://www.ssh.com/academy/ssh/sftp).


## 🔎 What's Here

This directory tree contains the following files:

```
📁   LabCAS Test Upload Data
    📄   README.md — this file
    📄   file1.data — random test data
    📁   subdir1
        📄   file2.data — random test data
        📁   subsubdir1
            📄   file4.data — random test data
        📁   subsubdir2
            📄   file5.data — random test data
            📄   file6.data — random test data
            📄   file7.data — random test data
    📁   subdir2
        📄   file3.data — random test data
```

All of the `.data` files are 4194304 bytes in size (4 megabytes); all files are unique.


## 📀 Maintenance

This directory is available on [GitHub](https://github.com/EDRN/labcas-test-data).

