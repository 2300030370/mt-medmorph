# MT MedMorph

## Folder Structure

This project contains the folder structure for the MT MedMorph project, including:

- **frontend/**: Contains the React/Vite application.
- **backend/**: Contains the FastAPI application.
- **docker/**: Contains Dockerfiles and configurations.
- **kubernetes/**: Contains Kubernetes manifests.
- **docs/**: Contains project documentation.

## Getting Started

### Frontend
1. Navigate to the **frontend/** directory.
2. Install dependencies: `npm install`.
3. Start the development server: `npm run dev`.

### Backend
1. Navigate to the **backend/** directory.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the FastAPI application: `uvicorn main:app --reload`.

### Docker
To build and run the Docker container:
1. Navigate to the **docker/** directory.
2. Run: `docker-compose up`.

### Kubernetes
Deploy the application on Kubernetes:
1. Navigate to **kubernetes/**.
2. Apply the configs: `kubectl apply -f .`.

### Documentation
Documentation is available in the **docs/** directory.
