# hFiles-Project
# HFiles — Mini Medical Record Dashboard (Assignment)

**Project**: Mini Medical Record Dashboard (HFiles assignment)  
This repository contains a full-stack implementation of the HFiles mini medical record dashboard assignment, built as a monorepo with separate `frontend` and `backend` folders. The app supports user signup, profile editing, upload of medical files (PDF/images), file preview, download, and delete functionality — all handled via APIs. Source details and assignment requirements are used as the reference for this implementation. :contentReference[oaicite:4]{index=4}

## Tech stack
- Frontend: Next.js (App Router), Tailwind CSS (component-based UI)  
- Backend: ASP.NET / .NET (Web API) with MySQL (or preferred relational DB)  
- File storage: Stored on backend (server filesystem or cloud storage)  
These technologies align with the Full Stack Developer brief and the assigned technical suggestions. :contentReference[oaicite:5]{index=5}

## Features
- User signup and session-based authentication (or JWT as needed)  
- User profile management (email, gender, phone, profile picture)  
- Medical file upload (PDF/images) with file-type validation on backend  
- Files list with preview, view full-screen, and delete actions  
- APIs return standard HTTP codes (401 for unauthorized, 400 for bad requests, etc.) as required by the spec. :contentReference[oaicite:6]{index=6}

---

## Repo layout
