# CS50 Web: Lecture 11 Security  

## Outline
* Open-Source Software 
* HTML 
* Flask 
* Environment Variables 
* SQL 
* APIs 
* Javascript 
* Django 
* Testing, CI/CD 
* Scalability 
* What's Next? 

### Open-Source Software 
* There is potential for a lot of people noticing vulnerabilities in the code base. 
* Two-Factor Authentocation: not just username/password but with a phone/e-mail authentication code.  

### HTML 
* Source Code can be inspected on modern browsers and making a replicate fake version is extremely easy. 
* Fake Links to mislead users. 

### Flask 
* HTTP(s): requests can be read and changed in the routers. 
* Cryptography: encrypted messages. 
* How to send private key? - Public-Key Cryptography 

### Environment Variables 
* get env variables in the code to avoid exposing sensitive information 

### SQL 
* avoid storing plain password: use a hash function or an encryption algorithm. 
* Information leakage: figuring out who has an account on this website when prompt messages are shown. 
* SQL injection: inject always true SQL logic.  
* src: `injection` 

### APIs 
* Some might not be able to access all the API data. Introduce API key with permissions, rate limiting and route authentication. 

### Javascript 
* Cross-Site Scripting: inject bad JS code to user's browser to execute. 
* Also, JS code can be stored in database and then when rendering to the browser it will potentially run. 
* src: `xss0` `xss1`

### Django 
* Cross-Site Request Forgery: forge a request to some other website in order to take some action that the user might already be logged into. 
* Introduce a special token to prevent forgery. 

### Testing, CI/CD 
* giving Travis CI access to code base. 

### Scalability
* DoS Attacks: overloading the server 
* DDos Attacks: distributed DoS Attack - multiple computers trying to attack the server. 

### What's next? 
* Server-Side
* Client-Side
* Deploying Websites 
* 
