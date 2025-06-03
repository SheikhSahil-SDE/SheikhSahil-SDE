## Section-3:  Installation & Prerequisites
            
                      
            1. Create an AWS Acc. (Already Done)
            2. Create an IAM user with required permissions
                IAM is used for a) Authentication - User/Group
                              & b) Authorization - Roles/Permissions (Read/Write/Delete/Update)

            3. Created an EC2 Instance 
               CMD $ cd <directory where .pem/ppk file is located> //.pem for Linux or Mac && .ppk for windows
               CMD $ ssh -i file_name.ppk ubuntu@<Public IPv4 address>
               then yes
               CMD $ chmod 400/600 file_name.ppk/.pem
               $ sudo usermod -aG docker ubuntu //To give the access to docker my ubuntu (EC2 instance)


            4. Install Docker
               
            5. Install Kubectl
                        1. Download the latest release with the command: $ curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
                        <img src="" width="1000" height="450">
                        2. Validate the binary (optional): $  curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl.sha256"
                           Validate the kubectl binary against the checksum file: $ echo "$(cat kubectl.sha256)  kubectl" | sha256sum --check
                            <img src="" width="1000" height="450">
                        3. Install kubectl: $ sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
                        4. Test to ensure the version you installed is up-to-date: $ kubectl version --client
                         <img src="" width="1000" height="450">


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
                <img src="" width="1000" height="450">
                $ terraform -help plan                                   

## Section-4:  Run the project locally without Kubernetes             
           

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



# Section-5: Containerization of the project 


                                                                   
# Section-6: Docker Compose Overview


                                                                   
# Section-7: Need for Container Orchestration


                                                                   
# Section-8: IaC (Infrastructure as Code) using Terraform


                                                                   
# Section-9: Deploying Project to Kubernetes


                                                                   
# Section-10: Custom domain configuration for the project


                                                                   
