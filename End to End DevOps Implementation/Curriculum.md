## Section-3:  
            
            Installation & Prerequisites
            
            1. Create an AWS Acc. (Already Done)
            2. Create an IAM user with required permissions
                IAM is used for a) Authentication - User/Group
                              & b) Authorization - Roles/Permissions (Read/Write/Delete/Update)

            3. Created an EC2 Instance 
               CMD $ cd <directory where .pem/ppk file is located>
               CMD $ ssh -i file_name.ppk ubuntu@<Public IPv4 address>
               then yes
               CMD $ chmod 400/600 file_name.ppk

            4. Install Docker
               
            5. Install Kubectl

            6. Install Terraform

                 $ sudo apt-get update && sudo apt-get install -y gnupg software-properties-common

                 Install the HashiCorp GPG key. $ wget -O- https://apt.releases.hashicorp.com/gpg | \
                                                  gpg --dearmor | \
                                                  sudo tee /usr/share/keyrings/hashicorp-archive-keyring.gpg > /dev/null

                 Verify the key's fingerprint. $ gpg --no-default-keyring \
                                                --keyring /usr/share/keyrings/hashicorp-archive-keyring.gpg \
                                                --fingerprint

                Add the official HashiCorp repository to your system: $ echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(grep -oP '(?<=UBUNTU_CODENAME=).*' /etc/os-release || lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list

                Download the package information from Hashicorp: $ sudo apt-get install terraform

                $ terraform -help
                $ terraform --version
                $ terraform -help plan                                   

## Section-4: 
            
            Run the project locally without Kubernetes 

            Checked docker compose: $ docker compose -h
            
            Cloned Git Repo: $ git clone https://github.com/iam-veeramalla/ultimate-devops-project-demo.git
            
            Changed directory to ==> ultimate-devops-project-demo: $ cd ultimate-devops-project-demo

                        $ pstree
                        $ htop 
                        $ top
                        $ ps / $ ps aux
                        $ ls -ltr
                        $ netstat -tuln
                        $ sudo tcpdump -i <Primary_Network_Interface_name> port <PORT>
                        $ traceroute <website>






                                                                   
