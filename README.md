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
   <ul>
     <li>Client sends credentials(username and password)</li>
     <li>Server validates credentials</li>
     <li>Server create a Token and sends it back to the client</li>
     <li>Client Uses this Token for each request</li>
     <li>Server validates this token everytime when teh client makes a request</li>
   </ul>
   You can find full documentation here: https://github.com/jwtk/jjwt#overview
</p>
