# spring-security-4-JWT

<h2>Why JSON Web Tokens?</h2>
<p> 
   <ul>
     <li>+Fast</li>
     <li>+Stateless</li>
     <li>+Used across many services</li>
     <li>-Compromised Secret Key</li>
     <li>-No visibility to logged in users</li>
     <li>-Token can be stolen</li>
   </ul>
</p>

<h2>How does it work?</h2>
<p> 
   Client sends credentials(username and password) to the server, then server validates credentials and creates Token and sends it back to the client. Now client uses this token for each request and server validates this token whenever a new request from that client is recieved.
</p>
