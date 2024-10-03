FROM python:latest
WORKDIR /App
COPY req.text  /App
RUN pip install -r req.text
COPY app.py . 
ENTRYPOINT ["python3"]
CMD ["app.py"]
EXPOSE 3000
  
