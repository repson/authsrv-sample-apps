## Angular Sample App

To run the sample follow these steps:

Set the Allowed Callback URLs in the Application Settings to

```
http://localhost:4200
```

Set Allowed Web Origins in the Application Settings to

```
http://localhost:4200
```

Set Allowed Logout URLs in the Application Settings to

```
http://localhost:4200
```

Make sure Node.JS LTS is installed and execute the following commands in the sample's directory:

```
npm install && npm start
```

You can also run it from a Docker image with the following commands:

```
# In Linux / macOS
sh exec.sh
# In Windows' Powershell
./exec.ps1
```