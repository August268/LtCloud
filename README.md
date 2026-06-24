# LtCloud - A self-hosted cloud storage

This is a project for personal use so this is where I will write the documentation and progress of the project. 

---
# Data flow

<img width="816" height="508" alt="image" src="https://github.com/user-attachments/assets/ff12a2cc-b01a-4ef7-9f44-20dee316b0ee" />

The client will send requests which will be redirected to the backend via a cloudflare tunnel. The backend will then send file-related requests to the MinIO storage container and database-related requests to the Postgresql container.

# Proxmox VE setup

<img width="305" height="311" alt="image" src="https://github.com/user-attachments/assets/01d353de-45bb-438a-8f17-57861599af51" />

# Next steps (Rough plan)

- Add all necessary apis on the backend
- Add a login feature for security
- Develop a mobile app for desktop and android using Kotlin Compose.
