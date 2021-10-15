
--> สร้าง env :
```bash
# ถ้าใช้ระบบปฏิบบัติการ Windows
virtualenv env
# ถ้าใช้ระบบปฏิบบัติการ Linux or Mac
python -m venv env
```

--> Activate env :
```bash
# ถ้าใช้ระบบปฏิบบัติการ Windows
.\env\Scripts\activate
# ถ้าใช้ระบบปฏิบบัติการ Linux or Mac
source env/bin/activate
# Install requirements
pip3 install -r requirements.txt
```

#

### รันแอป

--> run the Notes App :
```bash
python manage.py runserver
```

> server http://127.0.0.1:8000/