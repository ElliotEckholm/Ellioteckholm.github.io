FROM tiangolo/uvicorn-gunicorn-starlette:python3.7

RUN pip install requests
RUN pip install starlette
RUN pip install aiohttp
RUN pip install aiofiles
RUN pip install uvicorn
RUN pip install jinja2



COPY ./app /app

WORKDIR /app

EXPOSE 81
