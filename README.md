# OTRS-Mini-Admin
- For OTRS CE 6.0.x
- Allow part of admin function to mini-admin user

Case Reference: https://forums.otterhub.org/viewtopic.php?f=62&t=41871  
So the module in the discussion is 'AdminGenericAgent'  

1. Create group called mini-admin. And assigned an agent under it (rw).

2. To allow mini-admin users to access the module, find these setting and add additional value at Group parameter (mini-admin)
  
      To Access Admin Module and Its Navigation (General)
          - System Configuration > Frontend::Module###Admin  
          - System Configuration > Frontend::NavigationModule###Admin  
          
      To Access AdminGenericAgent and Its Navigation (Generic Agent) 
          - System Configuration > Frontend::Module###AdminGenericAgent  
          - System Configuration > Frontend::NavigationModule###AdminGenericAgent  
          

[![download.png](https://i.postimg.cc/FKgqx6qs/download.png)](https://postimg.cc/FfzDrTN2)
          
     
          
