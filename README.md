Penulis: [manhakkim](https://www.twitter.com/imposteruck)

# Pengenalan
Bab ini berisi pengenalan mengenai Pingpong

## [PingPong](https://www.pingpong.build/PingPongWhitepaperV0.1.2.pdf)
> [!NOTE]
> The world's first DePIN liquidity aggregator. Turning computational resources into a new form of DeFi liquidity. Get the maximum DePIN mining yield from PINGPONG money market!

# Tutorial Deploy Smart Contract
Bab ini berisi tutorial cara menjalankan Light node

Mining Pingpong Pakai Narasi DEPIN

## Daftar AKUN

- Daftar pakai google : https://harvester.pingpong.build/login
- Pilih Tambah Perangkat dan atur nama perangkat

- Install Docker
```
sudo apt install apt-transport-https ca-certificates curl screen software-properties-common -y && curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable" && sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin -y
```
- Download Pingpong Di VPS

```
wget https://pingpong-build.s3.ap-southeast-1.amazonaws.com/linux/latest/PINGPONG; chmod +x PINGPONG
```

- Running Screen

```
screen -S pingpong
```


- Back ke [Pingpong Device](https://harvester.pingpong.build/devices)
- Add Device
- Copy Device_Id (jangan disimpan dulu)

```
./PINGPONG --key Device_Id
```


- Back ke : [Pingpong Device](https://harvester.pingpong.build/devices)
- Input Nama
- Pilih Usage Priority (Optional)
- Klik LetsGO

## Help

Join komunitas [Discord ZuperHunt](https://t.co/n7TeWVlA48) jika kamu ada pertanyaan.
