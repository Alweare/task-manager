FROM python:3.12

WORKDIR /app
COPY . /app/

RUN pip install -r requirements.txt
LABEL maintainer="Yanis le Boss"
LABEL description="Image d'une sombe app Python"
LABEL version=1.0
EXPOSE 8000
CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "8000"]
