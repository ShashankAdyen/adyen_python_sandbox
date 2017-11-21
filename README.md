# adyen_python_sandbox
Snippets of code to communicate with the Adyen payments server

## Setup:
Add authentication credentials to /cgi-bin/submit.py

## Start
Start a server in the root directory using
```shell
python3 -m http.server --cgi 8000
```

## Troubleshooting
If you get permission problems, run
```shell
chmod +x cgi-bin/submit.py
```