## Python Sample App

To run the sample follow these steps:

Set the Allowed Callback URLs in the Application Settings to:

```
http://localhost:3000/callback
```

Set the Allowed Logout URLs in the Application Settings to:

```
http://localhost:3000
```

Make sure Python is installed and execute the following commands in the sample's directory:

```
pip install -r requirements.txt
python3 server.py
```

You can also run it from a Docker image with the following commands:

```
# In Linux / macOS
sh exec.sh
# In Windows' Powershell
./exec.ps1
```
