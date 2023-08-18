### Install Script Di Termux
```python
termux-change-repo
pkg update && pkg upgrade -y
pkg install python -y
pkg install git
git clone https://github.com/ferlyafriliyan/CreateFB
cd CreateFB
pip3 -r install requirements.txt
```
### Untuk Jalankan Script
```python
python create.py
```
