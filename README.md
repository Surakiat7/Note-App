
--> Create a virtual environment :
```bash
# ถ้าใช้ระบบปฏิบบัติการ Windows
virtualenv env
# ถ้าใช้ระบบปฏิบบัติการ Linux or Mac
python -m venv env
```

--> Activate the virtual environment :
```bash
# ถ้าใช้ระบบปฏิบบัติการ Windows
.\env\Scripts\activate
# ถ้าใช้ระบบปฏิบบัติการ Linux or Mac
source env/bin/activate
```
pip3 install -r requirements.txt

#

### รันแอป

--> To run the Notes App, we use :
```bash
python manage.py runserver
```

> server will be started at http://127.0.0.1:8000/