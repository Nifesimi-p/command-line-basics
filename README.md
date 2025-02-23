## command-line-basics

### Navigate to your projects folder from Week 1
cd /path/to/your/project

### Initialize it as a Git repository
git init

### Add all files to the staging area
git add .

### Commit the files with a meaningful message
git commit -m "Initial commit"

### Create a repository on GitHub named my-first-project (done on GitHub UI)

### Link the local repository to the remote
git remote add origin https://github.com/Nifesimi-p/my-first-project.git

###Push your changes to GitHub
git push -u origin main

### Clone your my-first-project repository to a new folder
cd /path/to/new/folder
git clone https://github.com/Nifesimi-p/my-first-project.git

### Navigate into the cloned repository
cd my-first-project

### Add a new file listing your programming goals
echo "My programming goals include mastering Git and GitHub for version control, learning a backend framework like FastAPI, building full-stack projects, automating tasks with scripts, deploying applications using AWS, setting up CI/CD pipelines, and gaining expertise in Kubernetes and cloud infrastructure tools like Terraform." > goals.txt

### Add the new file to staging
git add goals.txt

### Commit the changes
git commit -m "Added goals.txt with programming goals"

### Push the changes to GitHub
git push origin main

 ### Screenshots
 

 ![image1](./img1.png)
 ![image2](./img2.png)
 ![image3](./img3.png)
 ![image4](./img4.png)


