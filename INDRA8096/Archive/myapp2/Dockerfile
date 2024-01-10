FROM python:3.10-bookworm

WORKDIR /
COPY app.py .
RUN pip install Flask
EXPOSE 5001

ENTRYPOINT [ "python","-m","flask","run","--host=0.0.0.0","--port=5000" ]
