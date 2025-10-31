# Basic Task Manager

## Features
- **CRUD**: Add, toggle, delete tasks
- **Filtering**: All / Active / Completed
- **Persistence**: localStorage fallback + in-memory backend
- **Responsive**: Mobile-first with Tailwind CSS
- **Tech**: .NET 8 Minimal API + React + TypeScript + Axios

## Endpoints
| Method | URL               | Action               |
|--------|-------------------|----------------------|
| GET    | `/api/tasks`      | List all             |
| POST   | `/api/tasks`      | Create (body: `{description}`) |
| PUT    | `/api/tasks/{id}` | Update status/description |
| DELETE | `/api/tasks/{id}` | Delete               |

## Local Development
```bash
# Backend (.NET 8)
cd backend
dotnet run

# Frontend
cd frontend
npm install
npm run dev
