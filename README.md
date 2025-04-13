# OneConnectApp

**A production-grade, cloud-native integration platform** modeled after SAP-connected enterprise applications.  
Simulates authentication (EntraID), CMS content (Kentico), and SAP API workflows using AWS-native services and React.

---

## Tech Stack

- **Frontend:** React.js + Auth0 + Axios
- **Backend:** AWS Lambda, API Gateway, Secrets Manager
- **CMS Proxy:** Strapi or Contentful
- **Authentication:** Auth0 (simulates ENTRAID)
- **Database:** DynamoDB / PostgreSQL

---

## Architecture Overview

> See: `architecture/oneconnect-architecture.png`

---

## Features

- Secure login and token handling
- Serverless API with token verification
- Dynamic content loading via CMS proxy
- SAP-like system API simulation with token reuse
- Secrets management

---

## Getting Started

1. Clone the repo
2. Run `npm install` inside `frontend/`
3. Set up Auth0 and paste keys in `.env`
4. Deploy backend Lambda via AWS Console or Serverless Framework

---

## License

This project is not open source.  
All rights reserved © 2025 Sudhanshu Shekhar.  
Unauthorized use, reproduction, or distribution of this code is strictly prohibited.

