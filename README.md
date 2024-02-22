# gitdemo1
my world git
To commit and push in Git Bash in an EC2 instance, you can follow these steps:
Connect to your EC2 instance: using SSH. You can use the following command:
ssh -i <pem file> <username>@<instance public IP>
Use code with caution.
Learn more
Navigate to the directory: where your code is located.
Add your changes to the staging area: using the git add command. For example, to add all the changes in the current directory, you can use the following command:
git add .
Use code with caution.
Learn more
Commit your changes: using the git commit command. You will need to provide a commit message that describes your changes. For example, you can use the following command:
git commit -m "Added new feature"
Use code with caution.
Learn more
Push your changes to the remote repository: using the git push command. For example, to push your changes to the master branch, you can use the following command:
git push origin master
Use code with caution.
Learn more
Here is an example of the complete process:
ssh -i my_key.pem ubuntu@192.168.1.100

cd my_project

git add .

git commit -m "Added new feature"

git push origin master
Use code with caution.
Learn more
