## *Assignment Overview:*

> This assignment requires the candidate to set up a full-stack application that consists of a frontend and a backend component, with a PostgreSQL database. The goal is to demonstrate your ability to configure, run, and connect different services using Docker.


### Instructions:

> ### Fork/Clone the Repository:

- Start by forking or directly cloning this repository to your local machine.
```
git clone <repository-url>
cd <repository-folder>
```
> ### Project Structure:


The application is located in the `assignment/` directory, which contains two main components:
- Backend: Located in the `backend/` folder.
- Frontend: Located in the `frontend/` folder.

- Environment Variables:

    Create the necessary .env file required for the services to run properly. Ensure that you include all the required environment variables.

> ### Docker Setup:

Each folder contains its respective Dockerfile named appropriately. *You will need to make adjustments/troubleshoot to ensure everything works seamlessly.*
The backend should work with a PostgreSQL database for full functionality.

- Run PostgreSQL Database:

> You need to run the PostgreSQL database in a Docker container along with the backend and frontend services.
Using Docker Compose or

> You need to run all the applications along with the PostgreSQL in container.

- Creating a docker compose YML file

> ### Accessing the Application:

Once all services are running:
- The frontend should be accessible at http://localhost:3000.
![Screenshot (38)](https://github.com/user-attachments/assets/47317976-af31-4244-8df1-42b713e67b3b)

- The backend (FastAPI) should be accessible at http://localhost:8000/docs for the Swagger UI.

![Screenshot (37)](https://github.com/user-attachments/assets/09190872-d8cf-4fc1-9dcb-e6370268cc5f)

- PostgreSQL should be running on its default port 5432.
  ![Screenshot 2025-01-15 002644](https://github.com/user-attachments/assets/89a23783-20b8-4541-a395-a0c9368e886c)


> ### User Interface:

The frontend should prompt you for *signup* and *login* operations. You've to create a user and then login using that credentials to show that the communication between frontend and backend has been made correctly.
After successful operations, the UI should provide appropriate feedback messages.
