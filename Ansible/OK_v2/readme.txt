#Before you excute ansible playbook, your must create a EFS on the AWS, then you get my mount DNS name EFS ( can use Teraform create EFS)

#After you let go and edit file Grafana to EFS for /roles/efs/tasks/main.yml
#You must change target ID by me DNS name
#mount -t nfs4 fs-52bb2d19.efs.us-east-1.amazonaws.com:/ /efs

#tfs-52bb2d19.efs.us-east-1.amazonaws.com (my DNS name EFS)

#ansible-playbook granfana-efs.yml