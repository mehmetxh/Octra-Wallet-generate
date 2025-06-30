1) phyton yükleyelim
```bash
sudo apt install python3 python3-pip python3-venv python3-dev -y

2) CLı yükleyelim

```bash
git clone https://github.com/octra-labs/octra_pre_client.git
cd octra_pre_client

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

cp wallet.json.example wallet.json

