install aws cli

          curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
          unzip awscliv2.zip
          sudo ./aws/install
          
install java

          sudo apt-get install openjdk-11-jdk
          java --version

install python

          sudo apt-get install python3.6
          python3 --version

install brew

          /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

          echo >> /home/Arulraj/.bashrc
          echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> /home/Arulraj/.bashrc
          eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"


install databricks cli 

