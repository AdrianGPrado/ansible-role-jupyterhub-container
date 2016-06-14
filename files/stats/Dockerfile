FROM python:3

RUN pip install requests python-dateutil

RUN mkdir /srv/stats
WORKDIR /srv/stats
ADD log_activity.py srv/stats/log_activity.py

ENTRYPOINT ["python", "log_activity.py"]
