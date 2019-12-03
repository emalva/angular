***************************************************
* AWS
***************************************************
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html#ec2-launch-instance_linux
chmod 400 /home/manito/datos/aws/t2microeam.pem
ssh -i /home/manito/datos/aws/t2microeam.pem ec2-user@ec2-18-221-28-120.us-east-2.compute.amazonaws.com

***************************************************
* scripts for ec2 instance
***************************************************
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.1/install.sh | bash
. ~/.nvm/nvm.sh
nvm install node
node -e "console.log('Running Node.js ' + process.version)"
npm install bootstrap font-awesome
sudo yum update -y
sudo yum install git -y
git version
git clone https://github.com/DeborahK/Angular-GettingStarted.git

--TODO
renombrar carpeta

npm install

http://ec2-18-221-28-120.us-east-2.compute.amazonaws.com:4200
http://18.221.28.120:4200/
https://medium.com/@nishankjaintdk/setting-up-a-node-js-app-on-a-linux-ami-on-an-aws-ec2-instance-with-nginx-59cbc1bcc68c
