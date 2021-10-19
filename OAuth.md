<p align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Oauth_logo.svg/270px-Oauth_logo.svg.png"></p>

OAuth is an open standard for access delegation, commonly used as a way for Internet users to grant websites or applications access to their information on other websites but without giving them the passwords.This mechanism is used by companies such as Amazon,[3] Google, Facebook, Microsoft and Twitter to permit the users to share information about their accounts with third party applications or websites.

Generally, OAuth provides clients a "secure delegated access" to server resources on behalf of a resource owner. It specifies a process for resource owners to authorize third-party access to their server resources without providing credentials.

---------------

## Token:<br/>
Modern authentication and/or authorization solutions have introduced the concept of tokens into their protocols. Tokens are specially crafted pieces of data that carry just enough information to either authorize the user to perform an action, or allow a client to get additional information about the authorization process (to then complete it). In other words, tokens are pieces of information that allow the authorization process to be performed. 

-------------

## Token types: <br/>

* <b>Access tokens:</b><br/>
Access tokens carry the necessary information to access a resource directly. In other words, when a client passes an access token to a server managing a resource, that server can use the information contained in the token to decide whether the client is authorized or not. Access tokens usually have an expiration date and are short-lived.

<p align="center"><img src="https://images.ctfassets.net/23aumh6u8s0i/6A134evBBeR2xOY6TWLyrN/a4aa3e21690a5787639a4163c0eb15e2/diag1"></p>


* <b>Refresh tokens:</b><br/>
Refresh tokens carry the information necessary to get a new access token. In other words, whenever an access token is required to access a specific resource, a client may use a refresh token to get a new access token issued by the authentication server. Common use cases include getting new access tokens after old ones have expired, or getting access to a new resource for the first time. Refresh tokens can also expire but are rather long-lived. Refresh tokens are usually subject to strict storage requirements to ensure they are not leaked. They can also be blacklisted by the authorization server.


<p align="center"><img src="https://images.ctfassets.net/23aumh6u8s0i/4UuGB50z9WSljLC3jd7CQ8/a616650fa600d029c1df904fbfb62d18/diag2"></p>
