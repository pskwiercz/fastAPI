# fastAPI
FastAPI


## Books project

### Prepare env

<pre>
```bash
python3 -m venv fastapivenv
source fastapivenv/bin/activate
pip install "fastapi[standard]"
pip install "uvicorn[standard]"
pip list
  ```
</pre>

### Run app
uvicorn books:app --reload
fastapi dev books.py
fastapi run books.py
