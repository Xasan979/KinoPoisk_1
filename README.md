# KinoPoisk_1

```
███╗░░░███╗░█████╗░██████╗░███████╗  ██████╗░██╗░░░██╗
████╗░████║██╔══██╗██╔══██╗██╔════╝  ██╔══██╗╚██╗░██╔╝
██╔████╔██║███████║██║░░██║█████╗░░  ██████╦╝░╚████╔╝░
██║╚██╔╝██║██╔══██║██║░░██║██╔══╝░░  ██╔══██╗░░╚██╔╝░░
██║░╚═╝░██║██║░░██║██████╔╝███████╗  ██████╦╝░░░██║░░░
╚═╝░░░░░╚═╝╚═╝░░╚═╝╚═════╝░╚══════╝  ╚═════╝░░░░╚═╝░░░
   
             ██╗░░░██╗███████╗██╗░░██╗
             ██║░░░██║██╔════╝██║░██╔╝
             ╚██╗░██╔╝█████╗░░█████═╝░
             ░╚████╔╝░██╔══╝░░██╔═██╗░
             ░░╚██╔╝░░███████╗██║░╚██╗
             ░░░╚═╝░░░╚══════╝╚═╝░░╚═╝
```
## Task
https://disk.yandex.ru/i/Qy4d1ASip0S1FA

## ⚡ Quick Setup

### Windows
- Create venv and install requirements
    ```shell
    python -m venv venv
    venv\Scripts\activate
    pip install -r requirements.txt
    ```
- run script
    ```shell
    python run.py
    ```
- Open [http://127.0.0.1:25000/]() to test work 

### MacOS/Linux
- Create venv and install requirements
    ```shell
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```
- run script
    ```shell
    python3 run.py
    ```
- Open [http://127.0.0.1:25000/]() to test work 

## 🔧 Options

| Url|Methods|
|----|----|
|`/movies/`|`GET` params: status, page.|
|`/movies/<id>`|`GET`|
|`/genres/`|`GET` param: page|
|`/genres/<id>`|`GET`|
|`/directors/`|`GET` param: page|
|`/directors/<id>`|`GET`|
|`/auth/register`|`POST`|
|`/auth/login`|`POST`, `PUT`|
|`/user/`|`GET`, `PATCH`|
|`/user/password`|`PUT`|


## 📌 ToDo:
- [x] make models
  - [x] directors
  - [x] genres
  - [x] movies
  - [x] users
  - [x] favourites
- [x] make dao
  - [x] directors
  - [x] genres
  - [x] movies
  - [x] users
  - [x] favourites
- [x] make services
  - [x] directors
  - [x] genres
  - [x] movies
  - [x] auth
  - [x] users
  - [x] favourites
- [x] make views
  - [x] directors
  - [x] genres
  - [x] movies
  - [x] auth
  - [x] users
  - [x] favourites
- [ ] write comments


