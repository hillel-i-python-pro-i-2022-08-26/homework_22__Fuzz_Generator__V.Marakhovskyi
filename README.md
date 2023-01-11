# Homework # 22. (Fuzz Generator)

---
![Main workflow](https://github.com/hillel-i-python-pro-i-2022-08-26/homework_22__Fuzz_Generator__V.Marakhovskyi/actions/workflows/main-workflow.yml/badge.svg?branch=fuzz_generator)
![IDE](https://img.shields.io/badge/PyCharm-000000.svg?&style=for-the-badge&logo=PyCharm&logoColor=white)
![REPO](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
## 👨‍💻 Homework

Program generates all data and write it into different package files. Approximate time for generating 60 millions strs with length 5 is about 16-18 sec. on 12 CPUs. 
Quantity of CPU is dynamically selected, depends on machine where program starts.
All packed in Docker.


### 🎬 Run locally

Run an application locally with automatic installing of all requirements.

```shell
make homework-i-run
```

### 🎛️ Run in console with argparse
Run an application locally through console with variable argument. Default value - 5.

```shell
python main.py -word_len 4
```

### 📦 Run in docker

Run an application in Docker.

```shell
make d-homework-i-run
```

### 🛣️ Install pre-commit and dependencies:
```shell
make init-dev
```


### 🧽🪣 Purge

Delete all created artifacts from run.

```shell
make d-homework-i-purge
```
