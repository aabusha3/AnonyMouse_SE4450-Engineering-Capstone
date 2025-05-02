### Engineering Capstone Recap
- This engineering capstone was themed around cybersecurity. 
- As a team, we made a privacy-focused encrypted messaging service with a custom encryption stack, a hosted backend as a trusted server, and a local desktop client to ensure maximal security.
- The tech-stack for the backend was Python FastAPI to make use of websocket technology for live updates in a publisher-subscriber architecture with TLS for enhanced security, hosted on DigitalOcean Compute engine, and MongoDB for server-side storage.
- The tech-stack for the frontend was React with Electron and Vite framework to create a desktop client web application that works independently of the OS with an encrypted SQLite local database for isolation security to manage keys.
- The frontend uses an isolated encryption module written in Golang and compiled to WebAssembly; the security algorithm implements the Signal protocol but uses Schnorr NIZK for verification.
- The backend and frontend communicate using RESTful API architecture, and the project provides a full suite of features such as login, password reset, theme customization, correct message retrieval, user lookup, chatroom creation and deletion.

The repositories for the capstone can be found in the [link](https://github.com/orgs/SE4450-Team12/repositories) below. 
The backend is no longer hosted, so this service no longer works. 
Hosting the backend yourself won't work either.

https://github.com/orgs/SE4450-Team12/repositories
