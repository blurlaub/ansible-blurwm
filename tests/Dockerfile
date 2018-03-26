FROM urlaub/ansible:latest

WORKDIR /tests/tests

RUN pip install docker-py

CMD [ "ansible-playbook", "-i docker.py" "test.yml" ]
