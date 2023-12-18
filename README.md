# PhytonLibraryPackage
Cek paket Python library
$ pip list
Simpan seluruh paket library dari Python yang kita gunakan untuk bekerja
$ pip freeze > requirements.txt
Matikan virtual environment dan cek paket Python dan bandingkan dengan yang ada di dalam virtual environment
$ deactivate
$ pip list
Hapus virtual environment yang sebelumnya dibuat
$ rm -r .introduction-venv
Buat virtual environment lagi dan instal library yang sebelumnya
$ virtualenv .introduction-venv -p /usr/bin/python3.10
Aktifkan kembali virtual environment yang barusan dibuat
$ source .introduction-venv/bin/activate
$ pip install -r requirements.txt
