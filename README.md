# skripsirenaldi

1. Buat Folder pada laptop anda.  Misal di local disk D, Alan
2. Buka VSCODE lalu install ekstensi Jupiter ( https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter )
3. Setelah itu, download Datasetnya terlebih dahulu : ( Karena besar dan banyak saya letakkan di gdrive )
4. Link : https://drive.google.com/drive/folders/17Y5VwTAZPMrqvB--oVfzKgSzRu65zasn?usp=sharing
5. Extract semua file tersebut kedalam folder yang sama dengan nomor 1.
6. Buka VSCODE anda, pada terminal ketikkan  ' cd /d/Alan ' ( direktori anda membuat folder nomor 1 )
7. Buat Virtual Environtment dengan menggunakan 
#( virtual_env itu nama virtual environment anda, bisa di ganti )
python -m venv virtual_env

Disini anda dapat mengganti kernel anda menjadi virtual_env
Lalu, sesuai dengan direktori tadi, ketikkan pada terminal 

cd virtual_env
cd Scripts
activate


8. Lalu Install terlebih dahulu pip dengan

pip install -r /d/Alan/req.txt  ( lokasi anda meletakkan folder nomer 1)

lalu upgrade pip dengan

python.exe -m pip install --upgrade pip


#install dulu librarynya pake

pip install numpy padas tensorflow seaborn


Setelah semuanya telah dilakukan, buka file SKRIPSISOURCECODE4prasempro
( PASTIKAN FOLDER VIRTUAL ENVIRONTMENT SEFOLDER DENGAN DATASET5 )

# butuh instal jupiternotebook di vscode
# Perlu mengganti beberapa baris code terkait tempat menyimpan dataset dan test
# 
