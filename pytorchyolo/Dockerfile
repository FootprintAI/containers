from python:3.7

RUN apt-get update && apt-get install -y libgl1-mesa-dev

WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

CMD [ "python3" ]
