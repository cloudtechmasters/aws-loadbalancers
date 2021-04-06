# Network Load Balancer

# Pre-requisites
    Install httpd in both the servers
    server-1 should call by port "80"
    server-2 should call by port "8080"
# server-1
  ![image](https://user-images.githubusercontent.com/58024415/107868307-69e3d780-6ea9-11eb-8869-7509527e6a5b.png)
# server-2
  ![image](https://user-images.githubusercontent.com/58024415/107868745-c85e8500-6eac-11eb-935b-017ffed8698a.png)
# Create Target Group for 80 and 8080
  ![image](https://user-images.githubusercontent.com/58024415/107869102-8afbf680-6eb0-11eb-9c59-c849d4e40c45.png)
  
  Click on Target Group
  
  ![image](https://user-images.githubusercontent.com/58024415/107869114-a961f200-6eb0-11eb-95d1-bd88b62f87ac.png)

  Click on Create Target Group
  
  ![image](https://user-images.githubusercontent.com/58024415/107869816-25ac0380-6eb8-11eb-8aa3-f6af534349e5.png)

  Click on Next
  
  ![image](https://user-images.githubusercontent.com/58024415/107869824-66a41800-6eb8-11eb-8b98-bbcc8e624525.png)

  Click on Create Target Group
  
  ![image](https://user-images.githubusercontent.com/58024415/107869843-994e1080-6eb8-11eb-994a-8ff9c2708b04.png)
# Create Appliation Load Balancer  
  ![image](https://user-images.githubusercontent.com/58024415/107868427-4cfbd400-6eaa-11eb-9162-41b415535291.png)
  
  Click on Load Balancer
  
  ![image](https://user-images.githubusercontent.com/58024415/107868455-82082680-6eaa-11eb-9985-1b5cce1b875f.png)

  Click on Create Load Balancer

  ![image](https://user-images.githubusercontent.com/58024415/107869277-5db04800-6eb2-11eb-9458-6160fa5b201c.png)

  Click on Create
  
  ![image](https://user-images.githubusercontent.com/58024415/107869878-0e214a80-6eb9-11eb-9cf0-bf45a76d111d.png)

  Click on Configure Load Balancer
  
  ![image](https://user-images.githubusercontent.com/58024415/107869884-2d1fdc80-6eb9-11eb-8442-bf038d81b769.png)

  Click on Configure Security Settings
  Click on Configure Routing
  
  ![image](https://user-images.githubusercontent.com/58024415/107869891-4e80c880-6eb9-11eb-9f29-c8dc48282b6d.png)

  Click on Register Targets
  
  ![image](https://user-images.githubusercontent.com/58024415/107869897-6c4e2d80-6eb9-11eb-8557-c2277d67da0b.png)

  Click on Review
  
  Add one more Lister
  
  ![image](https://user-images.githubusercontent.com/58024415/107869904-8ee04680-6eb9-11eb-8c24-53ed42bebb25.png)

  Click on Listner
  
  ![image](https://user-images.githubusercontent.com/58024415/107869920-b46d5000-6eb9-11eb-8c3e-e00bf29f8e64.png)

  Click on Add listner
  
  ![image](https://user-images.githubusercontent.com/58024415/107869928-c51dc600-6eb9-11eb-8fc2-bd3aa1005581.png)

# Check output of Load Balancer
  ![image](https://user-images.githubusercontent.com/58024415/107869948-f1d1dd80-6eb9-11eb-8d4c-66e7af54bedd.png)

  Copy DNS name and check--> with port '80'
  
  ![image](https://user-images.githubusercontent.com/58024415/107869986-6f95e900-6eba-11eb-9a21-e9599704acb0.png)
  
  with port '8080'
  
  ![image](https://user-images.githubusercontent.com/58024415/107869988-77ee2400-6eba-11eb-8362-dcf5cd63bf05.png)
  
