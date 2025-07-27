FROM python:3.14.0rc1-alpine3.22
RUN pip install Flask
COPY rng.py /
CMD ["python", "rng.py"]
EXPOSE 80
