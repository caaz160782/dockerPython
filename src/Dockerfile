FROM python:3.11

WORKDIR /app

COPY . .

RUN pip install poetry

RUN poetry install

CMD ["poetry", "run", "uvicorn", "main:app", "--host", "0.0.0.0"]
