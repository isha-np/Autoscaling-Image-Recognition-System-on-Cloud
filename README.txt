GROUP MEMBER NAMES
Ravindra Aditya Singh
Manisha Nandkumar Phadke
Sagar Subbaiah Kuppanda Cariappa


MEMBER TASKS
1) Ravindra Aditya Singh
> design and implement the web tier (in project 1)
> download the Amazon Machine Image (AMI) from the AWS console
> set policies, create a new role for VM import, and an S3 to store the image of the web tier
> documenting the process in the report
> integration of components and testing

2) Manisha Nandkumar Phadke
> design and implement the controller and the autoscaling function (in project 1)
> importing the EC2 instance as an AMI into an S3 bucket
> setting up security tokens and debugging authentication errors
> architectural diagram and documentation
> configuration of OpenStack instance

3) Sagar Subbaiah Kuppanda Cariappa
> formulating and implementing the app tier (in project 1)
> setting up the web tier on OpenStack
> use the qemu image to create the OpenStack instance and connect it to the private network
> modifying the web tier code such that the OpenStack instance could execute the web tier code via ssh commands in the terminal
> integration, testing and documentation


AWS CREDENTIALS
Key Name = 'pass1'
Security Group ID = 'sg-045b79406ba4dd8b6'
AWS_SECRET_ACCESS_KEY=zvV4/aQ4oAVeZhmvm6jKebi/nb2v5/6u7yVWImlC
AWS_ACCESS_KEY_ID=AKIAZO5EGW22ZRV7TT4R


Floating IP Address: 172.24.4.107

PEM KEY FOR WEB-TIER SSH ACCESS
-----BEGIN RSA PRIVATE KEY-----
MIIEowIBAAKCAQEAqkxsAL5x5LERHaWgM6ig6RRHqEni/UdX0zXVEezkr4L1jY1M
yB6CmVI300AYZBZdFk0b7WTlLA6TUDd5Q6qDGlCMbeB9tyAn117gfMcYlGIsokfq
FzQB4gvVkd3eW3E6tBQIYbyxcsKKpHJLlqC8aBSvipTNw0fiJHaJ7n5qUJK03Ki2
bzuRlGFFgfzBx3SCt2DQ6PxrSG8cEGO9UseMecgTYGwBf9PDn4MiM1+JcTHDun4S
uQ4/EAAW2f0z7OPoVnXDY3xxR12spy+q2S0Jzyflf2Sq66J4D3X1iMtVOntwgL0y
osCA0bsAe/lHaC2TMUPvDX4/lqarvbu/OMsLxwIDAQABAoIBABE5u67zlIeiVW3f
Q+4Vv3j0AS+Hkbs2zS5jApNWl+cc4wOXaE3RsDob8+OdVxpAnNfVot6HVxr2unXh
tpVemPY/cYTnsS+lxAHn6eMVLGpN59/eUFJag1o/AjJH8+bh9CMk55gjQvutq+Jo
YTbyOTx54yusU4fOLJStnNQP22cc1RL0mavggb3BqAgUpaSDyRlbK7rUAWHJ4PNI
twcYU5JyfnvW40xrzD0lfr4rf7Ft7a4iMDyMpxRihvRcukTyLpxoyxn4lYwm0t2i
YIfyuQ8ew0UkUXf9X/Bm0kGHlYp8kuyU/0RTn2lxbprtfN9UqUbT8QKrytK+JGqb
QWKfkXkCgYEA8lMowaJCS016pBYafLLKf+ygerND2jUs83GhJ1XY1l+ccN8A4/we
Qgg1ZHqgjl7l6PwoB377F6uEs5qr8tuffUcRibYoVoexgp5+lHiVxiNp0IWf+gJF
fZu0+PX7S1PLlv4WghFdfkiNPvRNIMl/pD+pqX3EU98PqXBSltJ/5M0CgYEAs+i0
zOPAZ5gjYpmLAN/vCVoDrv48of950UxSvE36dtDU+m0hJ/fUh54cWkrx9kkcMgSq
N5v56XKN32i6duAM3R2Me/5clJltGZqBMcieVMjn97TtkGv52SIfzrhbD7rP7O3l
msZWKP89lmsNg9nmLTdMz1PWSTrQ2leeX75/0uMCgYEA1khlNP1oBDDqb2lAWN69
pOu5aWdWbAIz0r67lA4c5ky8CS+aGQDcPOYHWOf7TIpsYl+Agkhuf5rjiPMQdHxz
h5Ot1YooF4R8mxXOtzn+r6ynKIbRVYJmstFa8gCLDCx4Tvg3LSNv+njrtizQe1rT
rYnCXSfi0YvhzKKP1eEkyU0CgYB30riAcfwWwyRmKj+DYKIzB0nGxjuZ5a67sGq2
UfVMJ0CCXiakGRLrFGpr1NicoQrvYV4BVZg4XHyTXIw8WnMW3fRQLRR6QEmCsP31
K1oQvBKLT2yeMNwiOvEWXIEB0/liIvw2fnyqJ31cboZ816bPXLKCr6Lb+RlbItov
iJBX4wKBgBUvOMQ1SzOI7Zrqk5pRqu7B9k2qenBg6lROhO6YaF4KfSrqJRQVa3f6
BANSMahS5mBFyp13z2HRpFVuWothZXhFYn6sbKHDStVzknsczgJoN6qyCIKpSumg
eJJtc+RwDKcW/Pk44AO+9tyWBaNBSjqFu7/+LQRYA3+ASvHYUGan
-----END RSA PRIVATE KEY-----


SQS QUEUE NAMES
REQUEST SQS = requests_sss.fifo
RESPONSE SQS = response_sss.fifo

INPUT S3 BUCKET NAME = ccp1ip
OUTPUT S3 BUCKET NAME = ccp1op