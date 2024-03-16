FROM python:3.11

WORKDIR /my_app
COPY ./requirements.txt /my_app/

RUN pip install -r requirements.txt

RUN pip install --no-cache-dir -r requirements.txt

COPY ./ /my_app

CMD ["uvicorn", "my_app.app:fastapp", "--host", "0.0.0.0", "--port", "80"]