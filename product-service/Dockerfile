FROM node:24-alpine

WORKDIR /app

COPY requirement.txt .

RUN pip install --no-cache-dir -r requirement.txt

COPY . .

EXPOSE 3000

CMD ["python","app.py"]