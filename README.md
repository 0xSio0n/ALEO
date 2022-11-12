# ALOE-PROVER TESTNET

<b>ALEO</b> is Private applications.

- Source      : https://www.aleo.org/
- Source Code : https://www.bangpatengnode.site/

# Setup VPS
<table border="1px">
  <tr>
    <th>Komponen</th>
    <th>OS</th>
  </tr>
  <tr>
    <td>Spesifikasi</td>
    <td>Ubuntu 20.04 atau lebih tinggi.</td>
  </tr>
</table>


## Spesifikasi


- CPU       : 16-core
- RAM       : 16GB
- INTERNAL  : >100GB

# Tutorial Menjalankan Node
## Install Pemasangan Otomatis

    wget -O prover.sh https://raw.githubusercontent.com/bangpateng/Aleo-Prover/main/prover.sh && chmod +x prover.sh && ./prover.sh
    
<b>Installasi ini akan memakan waktu yang agak lama, jadi tunggu saja (10 Menit++)</b>

## Create Wallet

    snarkos account new
    
<b>REMINDER!! Jangan Lupa Simpan Account Kalian</b

## Run Prover

    cd snarkOS
    screen -R prover
    
#####
    ./run-prover.sh
    
- Masukkan Private Key kalian
- `CTRL + A D` untuk keluar dari screen
- Untuk masuk ke screen kembali copy code ini `screen -Rd prover`

<b> DONE, ALEO NODE SUDAH BERJALAN</b>

## Hapus / Uninstall ALEO
    rustup self uninstall
    rm -rf prover.sh
    rm -rf snarkOS
