# Description
Educational platform that personalizes learning materials and provides AI recommendations based on user activity.
Features include study tools (assignments, quizzes, spaced repetition), gamification elements, and synchronization
between web and mobile applications

Demo link: https://ai-educational-platform-frontend-95.vercel.app/ (only frontend is deployed, so no backend functionality is available)

## Activation

### Frontend

```
cd frontend/frontend
npm install
npm run dev
```

### Backend

#### Mac/Linux:

```
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

#### Windows (Powershell):

```
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

### Mobile

```
cd mobile
npm install
npx expo start
```
