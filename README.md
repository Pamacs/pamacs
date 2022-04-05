<h1 align="center">Pamacs</h1>

Pamacs is a free and open-source solution for managing your passwords anywhere. The goal is to make it fully functionable, anonymous and secure.

## Concept

The backend of Pamacs is a very simple one, there is no need to overcomplicate it. The whole server side stuff is for storing minimal userdata (`random userid, Scrypt hashed password and register date`) and of course for storing passwords. It uses JsonWebTokens (JWT) for authentication.  
Clients can come in different flavors too, just like linux distros. It's linux, except you use them in different ways. Here you can use other's clients, or you can make your own one. It doesn't matter, since you are allowed to access the backend from any client.

## Backend
- The source of the backend can be found here:
- https://github.com/Pamacs/pamacs-backend/

## Clients
- Official Webclient: https://github.com/Pamacs/client_php
