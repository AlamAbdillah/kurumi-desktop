![Screenshot from 2023-05-01 16-33-48](https://user-images.githubusercontent.com/115331322/235435627-57f239ff-5a4d-4ded-ba48-12edde362a94.png)

# kurumi-desktop
kurumi desktop adalah program asisten waifu yg ditampilkan didesktop computer.
Diprogram dengan python3 dan module pyqt5

## clone project
```sh
git clone https://github.com/AlamAbdillah/kurumi-desktop.git
```

## Install requirements
python version > 3
module
* playsound
* pyqt5
```sh
pip install -r requirements.txt
```
ubuntu
```sh
pip3 install -r requeriments.txt
```
ubuntu setel qt_platfrom ke xcb dengan export ... ke environment variabel
```sh
export QT_QPA_PLATFORM=xcb
```
## Path directory
jika menjalankan directory yang sama kosongkan path 
```python
self.path = ""
```

## Run program
windows
```sh
python main.py
```
ubuntu
```sh
python3 main.py
```
