### 1. Writing the app

- The code to build, train, and save the model is in the `test` folder.
- Implement the app in `main.py`

### 2. Setup Google Cloud 

- Create new project
- Activate Cloud Run API and Cloud Build API

### 3. Install and init Google Cloud SDK

- https://cloud.google.com/sdk/docs/install

### 4. Dockerfile

### 5. Cloud build & deploy

```
gcloud builds submit --tag gcr.io/<project_id>/<function_name>
gcloud run deploy --image gcr.io/<project_id>/<function_name> --platform managed
```