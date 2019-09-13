# TransformationAdvisor

Before you can install IBM Cloud™ Transformation Advisor Local (Beta), go to the Registration and download site to download the files and accept license terms. 
https://www.ibm.com/account/reg/in-en/signup?formid=urx-38642

Then, make sure that you meet the prerequisites for your operating system and follow the installation instructions.

Installation on Linux/MacOS
This task covers how to install IBM Transformation Advisor locally on Linux or MacOS. Before you start, ensure that the following products are installed:

-> Docker: <To be filled>
  
-> Docker Compose: https://docs.docker.com/compose/install/

1) Create a directory for the Transformation Advisor files, for example, ta_local. Copy the .zip file that you downloaded during the registration step into this directory and extract it: 
unzip transformationAdvisor.zip

2) To install Transformation Advisor locally, run the following command: 
./launchTransformationAdvisor.sh

3) Select 1 if you agree with the terms of the License.

4) Select 1 to install Transformation Advisor.

![GitHub Logo](/images/install_options.png)

5) After the installation is complete, you can access Transformation Advisor locally at the following URLs. The host name or IP address and port are provided by the installation program.
Linux: http://< host name >:< port >
MacOS: http://< IP Address >:< port 

Windows:

Watch this video to install on windows

1) Download Docker Desktop for Windows: Sign in to docker: 
https://hub.docker.com/editions/community/docker-ce-desktop-windows 

2) Create a folder, say "ta_local". Download the Docker Desktop for Windows executable to this folder.

3) Double click on the Installable and follow the instructions to complete the installation.
