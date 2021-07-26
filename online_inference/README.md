### Usage Instruction
~~~
Basic usage steps:

    cd online_inference
    docker build -t averpower/homework2 .
    docker run -p 8000:8000 averpower/homework2
    python make_request.py {num}
        num - number of requests
~~~

#### Other Options
~~~
You can pull docker image from https://hub.docker.com/:

    docker pull averpower/homework2:latest
    docker run -p 8000:8000 averpower/homework2
~~~
