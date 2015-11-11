# Signieren

## 1. Repo clonen / pullen:
    git clone https://github.com/freifunk-bingen/docs-ffbin.git
    git pull

## 2. Signieren:
    cd builds/
    ./sign.sh <PFAD_ZU_ECDSA_SECRET> manifest

## 3. commiten / pushen
    git add manifest
    git commit -a
    git push

