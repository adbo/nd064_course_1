FROM python:2.7
COPY /techtrends /app
WORKDIR /app
RUN pip install -r requirements.txt
RUN python2 init_db.py
EXPOSE 3111
CMD [ "python2", "app.py" ]
