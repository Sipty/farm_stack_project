# farm_stack_project

Basic CRUD functionality implemented with a React frontend and a Mongo backend. 

If you want to set up the project for your own use, all you'll need is a mongo server running on localhost, followed by sourcing the venv in backend and starting the fastapi app:
```
cd backend
source venv/bin/activate
uvicorn main:app --reload
```

Followed by starting the react app from the frontend folder:

```
cd frontend
npm start
```

Then go to localhost at port 3000 and feast thine eyes :) 