## Find more details in official link [Staqlab tunnel](https://tunnel.staqlab.com/)

- How it works?
   <br>Staqlab tunnel is a reverse-proxy service which creates a ssh tunnel between your localhost machine
                  and our server. <br>
      We act as a middleman between client (browser / postman / axios etc) and your localhost.
      <br>
      All request from such client are forward to the specified port on your machine.<br/>
                 
                  
-  How To Connect 
   - Download sarkaribabu-tunnel.sh using below command<br>
      ```
     Linux:
     wget https://raw.githubusercontent.com/abhishekq61/tunnel-client/master/linux/staqlab-tunnel.zip
     Mac:
     wget https://raw.githubusercontent.com/abhishekq61/tunnel-client/master/mac/staqlab-tunnel.zip
     Windows:
     wget https://raw.githubusercontent.com/abhishekq61/tunnel-client/master/windows/staqlab-tunnel.zip --no-check-certificate
     ```
   - Unzip Downloaded File<br>
 
    - Run Agent by typing command<br>
      ```    
      Linux / MacOs:
      ./staqlab-tunnel <port>
      
      Windows:
      staqlab-tunnel <port>
       ```
         - port is desired port where you local server is listening
     - Optional Parameters
       <br>
         ```
       ./staqlab-tunnel port=<port> hostname=<desired-domain>
       ```
         - desired-domain is domain of your choice which you want to point to your localhost
         
<br/><br/>         
   What is staqlab tunnel?<br/>
   Staqlab tunnel is a alternative to ngrok.com or serveo.com which allows you to expose your localhost to
   the public internet and get a public url which you could share anywhere and get a public domain name for it. ,i.e, 
   keeping it simple you could host server on your local machine.<br/>
   It also does have support for custom domain which makes it easy to develop webhooks integrations for shopify, nexmo,
   facebook, github, wordpress or similar 3rd party app developments <br/>
   
   Is custom domain supported?<br/>
   Yes, just pass the hostname parameter while initializing the tunnel client<br/>
   
   How secure it is?<br/>
   We use end-to-end ssh encryption between client browser to your system.End to encryption is accepted security standard worldwidr and makes man-on-middle
   attacks impossible.
   
   Do we store your private data? <br>
   No, we do not store any of your api requests /response data at our servers.We are just forward
   data from browser to your pc.<br>
   
   Supported System? <br/>
   We have installable clients for linux, mac and windows. Can also work for android if we receive requests for it.
   
   Can i integrate it with nodejs?<br/>
   Yes, we have npm library which you can add to our nodejs project.<br>
   Follow the npm link for the library [Npm Library](https://www.npmjs.com/package/@staqlab/staqlab-tunnel)
   
       
   Another miscellaneous usages includes<br/>
   - Hosting server on your machine
   - Creating public link for QA or beta users for pre-release testing
   - IOT development 
   - ESP8266 Integration
   - Devopps Purposes
   - Debugging code issues
   - Use it as a discord webhook url and get notified for git actions such as 
     git push, commit.
   - Use it as a campaign tracker, user discord webhook service  to get notified whenever a user 
     completed some action.
        
   Supported/Tested Webhook Integrations(not limited to, but includes)
   - Zoom Webhook integration
   - Shopify Webhook Integartion
   - Zapier Hooks
   - Zendesk Hooks
   - IFTTT Automation and DIY
   - Airtable Webhhoks     
   - Alexa Skill Development
   - Video Surveillance Hosting, e.g Contacam and simliar softwares
   
   Have a question / suggestion?<br/>
   Mail us at admin@staqlab.com 
