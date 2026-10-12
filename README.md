# Lab 5 - Postman and APIs

A Flask app that adds, gets, updates and deletes users in a SQLite database through a REST API.

## How to run

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

The app runs on http://localhost:5000 and creates `database.db` the first time it runs.

## Endpoints

| # | Endpoint | Method | Description |
|---|----------|--------|-------------|
| 1 | /api/users | GET | Get all users |
| 2 | /api/users/<user_id> | GET | Get one user by id |
| 3 | /api/users/add | POST | Add a new user |
| 4 | /api/users/update | PUT | Update a user |
| 5 | /api/users/delete/<user_id> | DELETE | Delete a user |

## Postman

The `postman` folder has the "Flask user app" collection and the environment with the `base_url` variable (`http://localhost:5000`). Screenshots are in the `screenshots` folder.
