Tutorial

1. Open https://github.com/open-ibc/ibc-app-solidity-template/tree/main
2. Klik Use template > Create new repository
![image](https://github.com/jukiardiansyah/polymer-dontbemad/assets/74748443/caad74ab-3d2e-439a-a2ec-40cd6bf9cc02)
3. Open Gitpod https://gitpod.io/new
4. Paste URL yg sudah di fork

5. Run di terminal Gitpod
  - curl -L https://foundry.paradigm.xyz/ | bash
  - source /home/gitpod/.bashrc
  - foundryup
  - npm install -g just-install
  - just install
  - cp .env.example .env
    Siapkan wallet EVM kosong dan isi faucet https://www.alchemy.com/faucets/optimism-sepolia & https://www.alchemy.com/faucets/base-sepolia
7. Buka file .env
![image](https://github.com/jukiardiansyah/polymer-dontbemad/assets/74748443/dff2ceed-d181-4b70-9ac2-ed9fa25ce3f0)
  - Nomor 1 isi private key wallet
  - Nomor 2 dan 3 ADD ALCHEMY_API_KEY buat OP Sepolia dan Base Sepolia (Tutor di https://docs.alchemy.com/docs/alchemy-quickstart-guide)
  - Nomor 4 dan 5 ADD BLOCKSCOUT_API_KEY OP dan Base (connect wallet) https://optimism-sepolia.blockscout.com/account/api-key & https://base-sepolia.blockscout.com/account/api-key
  - TENDERLY_TOKEN hapus saja
8. Run di terminal just do-it

