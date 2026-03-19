# OPEN-SOURCE-EX-1
Create a repository file  http://classroom.example.com/content/rhel9.0/x86_64/dvd/AppStream http://classroom.example.com/content/rhel9.0/x86_64/dvd/BaseOS
# Name : V.GuruRagav Ponjeevith
# Reg No : 212223220027
# Dept : Btech(IT)
# Steps involved:
## Step 1 : cd /etc/yum.repos.d/
## Step 2 : sudo vi classroom.repo
## Step 3 : 
### [AppStream]
### name=AppStream Repository
### baseurl=http://classroom.example.com/content/rhel9/x86_64/dvd/AppStream
### enabled=1
### gpgcheck=0

### [BaseOS]
### name=BaseOS Repository
### baseurl=http://classroom.example.com/content/rhel9/x86_64/dvd/BaseOS
### enabled=1
### gpgcheck=0
## Step 4 : dnf clean all
## Step 5 :dnf repolist

# Output:

<img width="953" height="955" alt="image" src="https://github.com/user-attachments/assets/44826d09-ef9b-4e29-9761-2ee49ee134f2" />


# Result :
## Thus the steps worked in Red hat lab (Terminal) 

