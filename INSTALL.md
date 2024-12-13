To init the system you need install the requeriments

in directory frontend execute:
'''sh
py4web setup apps
py4web set_password
py4web run apps
'''
in directory backend execute:
'''sh
uvicorn main:app --host 0.0.0.0 --port 8080 --workers 4
'''