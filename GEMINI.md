# Project Instructions for Gemini Agent

## 1. Core Workflow
1. **Plan First, Code Second:** Read existing controllers, models, and views first. Present a step-by-step plan and wait for approval before editing code.
2. **Minimal Edits:** Modify only the necessary files. Do not break existing API endpoints or database schemas.
3. **Verify Before Finishing:** Check PHP syntax, JS console errors, and API JSON responses before finishing.

## 2. Tech Stack & Architecture
* **Backend:** PHP 8+, CodeIgniter 4 (MVC + RESTful JSON APIs)
* **Frontend Web:** HTML5, CSS3 (Tailwind/Bootstrap), Vanilla JS / jQuery
* **Mobile App:** [Capacitor / React Native / Flutter] consuming CodeIgniter APIs
* **Database:** MySQL / MariaDB

## 3. Coding & Security Standards
* **CodeIgniter Security:** Always use Query Builder / prepared statements (prevent SQL injection), CSRF protection on web forms, and JWT/token auth for mobile APIs.
* **API Responses:** Return clean, consistent JSON (`status`, `message`, `data`) with proper HTTP status codes (200, 400, 401, 500).
* **SEO & Mobile Speed:** Keep web pages lightweight, responsive, and include proper meta/schema tags.
* **Secrets:** Never hardcode database credentials, JWT secrets, or payment keys—always use `.env`.