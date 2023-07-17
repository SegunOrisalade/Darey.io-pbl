# WEB STACK IMPLEMENTATION (LAMP STACK) IN AWS

## Connectiong to my EC2 instance
![project1submission1](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/3a45c3fc-e2e7-420f-bc69-e58803c001fa)

![project1sub2connecting to ec2 terminal](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/57deefc0-c266-4b32-aee3-60cb1dc87e81)

## STEP 1 — INSTALLING APACHE AND UPDATING THE FIREWALL

### apt update
![project1sub2 apt update](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/b92582c1-b1ec-447a-9730-c143e2ebf311)

### Installed apache2 and status verified
![project1sub3 install apache2 and stautus verification](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/696c55e5-fee7-4415-9736-b48a0b6874ae)

 ### Add a rule to EC2 configuration to open inbound connection through http port 80:
 ![project1sub2 add http port 80](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/ecf3fa08-e29d-41e6-b107-821264550188)

### curl http://localhost:80
![project1sub2 curl httplocalhost80](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/22aae814-89b9-4d57-b1e0-fc93daa795c4)

### Testing Apache HTTP server
![project1sub5 Testing apache server](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/092d0743-8e8f-4648-9974-fdda4778f35b)

## STEP 2 — INSTALLING MYSQL
![project1sub6 installing mysql](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/983cffa8-7cab-48b2-b386-eb26d7b2a941)

![project1sub2 mysql](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/bbabbedf-6ad4-4d04-bd6e-723c1c3e0114)

## STEP 3 — INSTALLING PHP
![project1sub8 installing PHP](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/2df391bb-e97b-476a-8fe9-87e8c1050080)

### php -v
![project1sub9 php-v](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/5e500f2d-d624-4fd3-8aea-b9034dfb64f4)

## STEP 4 — CREATING A VIRTUAL HOST FOR YOUR WEBSITE USING APACHE
![project1sub2 creating virtual host](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/7e5cc155-edb8-4359-9fbb-7749e3f461dc)

![project1sub2 creating virtual host2](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/09bb631a-4475-46a2-8502-3de0abaee920)


STEP 5 — ENABLE PHP ON THE WEBSITE
![project1sub3 enabling php](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/9b633477-0b50-4752-b645-1687a625a72b)

![project1sub2 enabling php22](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/507becfd-1404-455c-977c-9669daef6ec8)

![project1sub2 enabling php23](https://github.com/SegunOrisalade/Darey.io-pbl/assets/135872037/eb957234-5db2-4023-839b-3d113b747630)


