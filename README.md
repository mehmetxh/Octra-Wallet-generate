# Octra-Wallet-generate
herkese selam arkadaşlar octra bir faucet açmış ve validator değilseniz bile ilerdeki işlemler için token almanızı söylüyor o yüzden çıtırdan bir cüzdan oluşturacağız.

Hello everyone, Octra has opened a faucet and even if you are not a validator, it tells you to buy tokens for future transactions, so we will create a wallet from scratch.

````curl -fsSL https://bun.sh/install | bash````

```sudo ufw allow 8888```

`npm install -g bun`

``bun --version``

``git clone https://github.com/octra-labs/wallet-gen``

``cd wallet-gen``

``bun install``

``bun run build``

``bun start``

sonrasında http://ip:8888 ile tarayıcıya bağlanacağız ve generate cüzdan bölümü açılacak oradan kelime ve adresleri alacağız. 

Afterwards, we will connect to the browser with http://ip:8888 and the generate wallet section will open and we will get the words and addresses from there.

https://faucet.octra.network/

# Octra cüzdan işlemleri 
1) phyton yükleyelim
   ```bash
   sudo apt install python3 python3-pip python3-venv python3-dev -y

2) clı yükleyelim
   ```bash
   git clone https://github.com/octra-labs/octra_pre_client.git
   cd octra_pre_client
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   cp wallet.json.example wallet.json

3) 2 private key formatı var B64 formatında olanı gireceksiniz
   ```bash
   nano wallet.json
4) cli başlatalım
   ```bash
   python3 -m venv venv
   source venv/bin/activate
    python3 cli.py

5) evet seçenekleri kullanarak cüzdana bakiye gönderimleri sağlayabiliriz adres bulmak için
```bash
https://octrascan.io/

   
   



