# Setup AWS EC2 inctance on Linux (Free tier eligible)
If you don't have an account already then sign up on https://aws.amazon.com/console/

Once you are logged in search for EC2 in the searchbar on top

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-search-ec2.png?raw=true)

Click on Launch instance > Launch instance

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-launch-instance-main.png?raw=true)


Enter name of your application without spaces

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-name-server.png?raw=true)


Make sure next section matches these settings

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-application-os.png?raw=true)

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-instance-type.png?raw=true)


Click on create new key pair

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-keypair.png?raw=true)

Enter the keyname as shown and make sure other settings matches and click on create key pair

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-create-keypair.png?raw=true)


It will download a .ppk file, This is the private key that you will use to access your aws server in Putty etc.

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-search-ec2.png?raw=true)


Click on Edit in Network settings

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-network-settings.png?raw=true)


Scroll down and click on add security group rule

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-add-security-group.png?raw=true)


Make sure it matches these settings

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-security-group-2.png?raw=true)


Click on add security group rule again, and make sure it matches these settings

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-security-group-3.png?raw=true)


Click on add security group rule again, and make sure it matches these settings

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-security-group-4.png?raw=true)


Set the settings for configure storage as 

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-configure-storage.png?raw=true)


Click on launch instance

![alt text](https://github.com/DrZainulabdeen/setup-guides/blob/main/images/aws/ec2-launch-instance-final.png?raw=true)


It will take couple of minutes to create and run the server. After that go back to same EC2 page and click on instances. And the click on instance id



