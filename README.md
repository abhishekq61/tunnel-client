-  How To Connect
   - Download sarkaribabu-tunnel.sh using below command<br>
      ```
     Linux:
     wget https://raw.githubusercontent.com/abhishekq61/tunnel-client/master/sarkaribabu-tunnel-client-linux -O tunnel
     Mac:
     wget https://raw.githubusercontent.com/abhishekq61/tunnel-client/master/sarkaribabu-tunnel-client-macos -o tunnel
     Windows:
     wget https://raw.githubusercontent.com/abhishekq61/tunnel-client/master/sarkaribabu-tunnel-client-win.exe -o tunnel
     ```
   - Make above file executable by typing command<br>
      ```
     Linux:
     chmod +x ./tunnel
     ```
    - Run Agent by typing command<br>
      ```    
      ./tunnel <port>
       ```
         - port is desired port where you local server is listening
     - Optional Parameters
       <br>
         ```
       ./tunnel port=<port> hostname=<desired-domain> access-token=<access-token>
       ```
         - desired-domain is domain of your choice which you want to point to your localhost
         - access-token is your private auth token to authenticate yourself for accessing your purchased sarkaribabu domain
         
    