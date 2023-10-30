Download and run the AWS CLI MSI installer for Windows (64-bit):

https://awscli.amazonaws.com/AWSCLIV2.msi

Alternatively, you can run the msiexec command to run the MSI installer.


`C:\> msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi`
For various parameters that can be used with msiexec, see msiexec on the Microsoft Docs website. For example, you can use the /qn flag for a silent installation.


`C:\> msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi /qn`
To confirm the installation, open the Start menu, search for cmd to open a command prompt window, and at the command prompt use the aws --version command.


`C:\> aws --version
aws-cli/2.10.0 Python/3.11.2 Windows/10 exe/AMD64 prompt/off`


Commands:

`aws configure`

`aws ec2 describe-instances`