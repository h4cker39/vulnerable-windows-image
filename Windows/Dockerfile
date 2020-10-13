FROM python:3.8.1-windowsservercore
WORKDIR /app
ADD . /app
RUN pip install -r requirments.txt
EXPOSE 6645
ENV NAME Mine
CMD["python", "-v"]

