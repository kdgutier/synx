# Store Scrappers

Dependencies:
- pandas, numpy, matplotlib, sklearn, juyter

# install conda and create environment
https://conda.io/docs/user-guide/tasks/manage-environments.html
```console
remote_user@remote_host$ scp Anaconda3-5.1.0-Linux-x86_64.sh ec2-user@ip:/home/ec2-user/Anaconda3-5.1.0-Linux-x86_64.sh
remote_user@remote_host$ bash Anaconda3-5.1.0-Linux-x86_64.sh
remote_user@remote_host$ source .bashrc
remote_user@remote_host$ conda env create -f synx.yml
```
