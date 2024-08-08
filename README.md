<h1 align=center> object-detection-using-yolo5 </h1>

**End-to-End Sign-Language Project Implementation Using YOLO-5**

- Git clone the repository and define the template of the project
```bash
git clone https://github.com/-----
touch template.py
python template.py
```
- define setup.py file

- install the new env and requirements.txt

```bash
conda create -n signlang python=3.7 -y
conda activate hate
pip install -r requirements.txt
```
- define the logger

- define the exception handler

- create dataset
    - create file -> `data_generation.py`
    - we use roboflow for data annotation
    - get the data from roboflow and store it in github and S3 bucket