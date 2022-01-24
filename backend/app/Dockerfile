FROM python:3.9

WORKDIR /which_pitch/backend

COPY requirements.txt /which_pitch/backend
RUN pip3 install --upgrade pip -r requirements.txt

COPY . /which_pitch/backend

EXPOSE 8090

CMD python3 manage.py runserver 0.0.0.0:8090