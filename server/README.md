# AR Cut Paste local server

## Setup

```console
virtualenv -p python3.7 venv
source venv/bin/activate
pip install -r requirements.txt
```

## Run

Replace `123456` by your Photoshop remote connection password.

```console
python src/main.py \
    --basnet_service_ip="http://X.X.X.X" \
    --basnet_service_host="basnet-http.default.example.com" \
    --photoshop_password 123456
```
