# b2c-connect

⚠️ **Work in Progress**  
This project is currently under development. Features and structure are subject to change.

## 📋 Overview

`b2c-connect` is an open-source [ASP.NET Core Web API](https://docs.microsoft.com/en-us/aspnet/core/web-api/) project that integrates with **Azure AD B2C** using the **Resource Owner Password Credentials (ROPC)** flow. 
It provides endpoints to manage the full user lifecycle — including **signup, login, password reset, profile updates, and account status management** 

> This project is intended for trusted backend services where direct username/password authentication is acceptable. ROPC should be avoided in public or frontend applications.

## ✨ Features
- 🔐 User Signup & Login (via Azure B2C)
- 🔄 Password Reset & Update
- 👤 Profile Update
- ⚡ Account Status Update (enable/disable users)
- 📡 RESTful API endpoints
- 🟦 Built with ASP.NET Core & Azure AD B2C

## 🚀 Getting Started
> *Coming soon...*
> Basic instructions to run the project locally will be added once the initial build is ready.

## 🛠️ Tech Stack
- ASP.NET Core Web API
- Azure AD B2C
- Microsoft Identity Platform

## ⚠️ Security Considerations

This project uses the **ROPC (Resource Owner Password Credentials)** flow, which allows direct username/password login without user interaction. While useful for trusted backend services or legacy scenarios, it has the following limitations:

* Does not support social identity providers or multi-factor authentication.
* Less secure than interactive flows like Authorization Code flow.
* Should only be used in **confidential clients** such as server-side applications.

For more details, see [Microsoft’s ROPC documentation](https://learn.microsoft.com/en-us/azure/active-directory-b2c/ropc-custom).

---

## 🤝 Contributing
Not ready for external contributions yet. Stay tuned!

---

## 📄 License
This project is licensed under the **MIT License**.
