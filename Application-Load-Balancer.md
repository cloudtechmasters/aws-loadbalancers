# Application Load Balancer

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
  
  ![image](https://user-images.githubusercontent.com/58024415/107869198-563c6f00-6eb1-11eb-8420-422ef9b18c98.png)

  Click on Next
  
  ![image](https://user-images.githubusercontent.com/58024415/107869246-04e0af80-6eb2-11eb-9700-43caf15cfa49.png)
  
  Click on Create Target Group
  
  ![image](https://user-images.githubusercontent.com/58024415/107869267-3d808900-6eb2-11eb-9c2e-70d479fc897e.png)
# Create Appliation Load Balancer  
  ![image](https://user-images.githubusercontent.com/58024415/107868427-4cfbd400-6eaa-11eb-9162-41b415535291.png)
  
  Click on Load Balancer
  
  ![image](https://user-images.githubusercontent.com/58024415/107868455-82082680-6eaa-11eb-9985-1b5cce1b875f.png)

  Click on Create Load Balancer

  ![image](https://user-images.githubusercontent.com/58024415/107869277-5db04800-6eb2-11eb-9458-6160fa5b201c.png)

  Click on Create
  
  ![image](https://user-images.githubusercontent.com/58024415/107869319-ec24c980-6eb2-11eb-8f1a-d04587a6c2a8.png)

  Click on Create Security Settings
  Click on Configure Security Groups
  
  ![image](https://user-images.githubusercontent.com/58024415/107869363-5473ab00-6eb3-11eb-8181-d1e28b092ae1.png)

  Click on Configure Routing
  
  ![image](https://user-images.githubusercontent.com/58024415/107869371-67867b00-6eb3-11eb-9b15-f43ba457e3b9.png)

  Click on Next: Register Targets
  
  ![image](https://user-images.githubusercontent.com/58024415/107869396-900e7500-6eb3-11eb-81c2-32349b648277.png)

  Click on Review
  Click on Create
  
  ![image](https://user-images.githubusercontent.com/58024415/107869452-32c6f380-6eb4-11eb-9fed-d60246887901.png)

  Click on Add Listeners
  
  ![image](https://user-images.githubusercontent.com/58024415/107869468-791c5280-6eb4-11eb-8784-ba703eef9656.png)

  Click on Add listener
  
  ![image](https://user-images.githubusercontent.com/58024415/107869486-9a7d3e80-6eb4-11eb-9476-36dcb84e98d9.png)
 
# Check output of ALB using DNS name  
  ![image](https://user-images.githubusercontent.com/58024415/107869494-c3053880-6eb4-11eb-8c20-5c212b94d2f1.png)
  
  Copy DNS name and check in UI:
  With port '80'
  
  ![image](https://user-images.githubusercontent.com/58024415/107869499-dfa17080-6eb4-11eb-9e1b-f744f3647b26.png)
  
  With port '8080'
  
  ![image](https://user-images.githubusercontent.com/58024415/107869501-e92ad880-6eb4-11eb-9d38-8d2654a3f6c8.png)
