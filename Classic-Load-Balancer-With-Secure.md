# Classic Load Balancer With Secure Using ACM

# pre-Requisites
    Install httpd on two servers with different content of index.html
# server-1
  ![image](https://user-images.githubusercontent.com/58024415/107868307-69e3d780-6ea9-11eb-8869-7509527e6a5b.png)
# server-2
  ![image](https://user-images.githubusercontent.com/58024415/107868412-23db4380-6eaa-11eb-8f9d-1d56fcf62eb6.png)
# Create Classic load balancer
  ![image](https://user-images.githubusercontent.com/58024415/107868427-4cfbd400-6eaa-11eb-9162-41b415535291.png)
  
  Click on Load Balancer
  
  ![image](https://user-images.githubusercontent.com/58024415/107868455-82082680-6eaa-11eb-9985-1b5cce1b875f.png)

  Click on Create Load Balancer
  
  ![image](https://user-images.githubusercontent.com/58024415/107868472-9fd58b80-6eaa-11eb-891d-53412f3d221e.png)

  Click on Create
  
  ![image](https://user-images.githubusercontent.com/58024415/107871509-41b7a100-6ec8-11eb-9678-21024073b68c.png)

  Click on Next: Assign Security Group
  
  ![image](https://user-images.githubusercontent.com/58024415/107871527-7deb0180-6ec8-11eb-828b-9e37b03edc14.png)

  Click on "Next: Configure Security Settings"
  
  ![image](https://user-images.githubusercontent.com/58024415/107871538-9a873980-6ec8-11eb-8c58-c56d1e48332a.png)

  Click on "Next: Configure Health Check"
  
  ![image](https://user-images.githubusercontent.com/58024415/107871551-b68adb00-6ec8-11eb-91e7-53d39b27d053.png)
  
  Click on "Next: Add Instances"

  ![image](https://user-images.githubusercontent.com/58024415/107871564-caced800-6ec8-11eb-9312-d7cc4cf3a189.png)
  
  Click on "Next: Add Tags"
  
  ![image](https://user-images.githubusercontent.com/58024415/107871593-f356d200-6ec8-11eb-95a3-801a5e49812f.png)
  
  Click on "Review and Create"
  Click on "Create"
  
  ![image](https://user-images.githubusercontent.com/58024415/107871625-4a5ca700-6ec9-11eb-8740-12f3b3eb8bbc.png)

  Status of both servers showing OutOfService, need to wait until both the servers come to InService.
  
  ![image](https://user-images.githubusercontent.com/58024415/107871636-7841eb80-6ec9-11eb-9f67-cf2ca7bb9e4e.png)

# Check output of Loadbalancer with DNS name
  ![image](https://user-images.githubusercontent.com/58024415/107871674-c48d2b80-6ec9-11eb-9ea7-40e3b3eb64e6.png)
  
  Give DNS name in UI and check 
  
  ![image](https://user-images.githubusercontent.com/58024415/107871647-91e33300-6ec9-11eb-8827-e191fc891f8c.png)
  
  Ping DNS one more time and check
  
  ![image](https://user-images.githubusercontent.com/58024415/107871649-97407d80-6ec9-11eb-967d-48b106ce4732.png)
# Create Hosted zone with certificate
  [Hosted Zone](https://github.com/Naresh240/Hosted-Zone/blob/main/README.md)  
# Add Record in Hosted Zone with "httpd.awstraining9pm.tk"
  ![image](https://user-images.githubusercontent.com/58024415/107871729-3d8c8300-6eca-11eb-997c-38d38cfed8e6.png)
# Check output with DNS name
  https://httpd.awstraining9pm.tk/
  
  ![image](https://user-images.githubusercontent.com/58024415/107871963-585ff700-6ecc-11eb-9a1c-19311c808d2d.png)
  
  Refresh UI once and check
  
  ![image](https://user-images.githubusercontent.com/58024415/107871965-5dbd4180-6ecc-11eb-93f7-4bc9eb931a20.png)
