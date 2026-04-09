# Skill 16 - API Documentation for Full-Stack Student CRUD Application using Swagger

Full-stack Student CRUD application with:
- `backend/` -> Spring Boot REST API with Swagger/OpenAPI
- `frontend/` -> React app for testing CRUD operations in the browser

## Run Order

### Backend
```bash
cd "/Users/bhargavnagam/FULL STACK SKILL/Skill-16/backend"
mvn spring-boot:run
```

### Frontend
```bash
cd "/Users/bhargavnagam/FULL STACK SKILL/Skill-16/frontend"
npm install
npm run dev
```

## URLs
- Frontend: `http://localhost:5173`
- Backend API: `http://localhost:8083/students`
- Swagger UI: `http://localhost:8083/swagger-ui/index.html`
- OpenAPI JSON: `http://localhost:8083/v3/api-docs`

## Test Options
- Use the React frontend for add, update, delete, and list actions
- Use Swagger UI to inspect schemas, request bodies, responses, and validation errors
