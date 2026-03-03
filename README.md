# hrms-lite
Assignment for selection

mkdir backend
cd backend
python -m venv venv
source venv/bin/activate  # windows: venv\Scripts\activate
pip install fastapi uvicorn sqlalchemy psycopg2-binary pydantic email-validator

to run the code on local 
uvicorn main:app --reload

swagger docs on 
http://127.0.0.1:8000/docs
