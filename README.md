# golang-testing-task

Task:
Build API to check if a list of given numbers are primes. API should only have a single
'POST' endpoint to accept the request.
The request body must be a slice of integers, otherwise return an error.
If the request is valid, return a slice of booleans either the number was prime or not.


<img width="613" alt="image" src="https://user-images.githubusercontent.com/61024343/214285372-dc87604b-7ee0-46ee-b2e3-36d6cb43808c.png">



The project was made taking into account further expansion, the architecture was chosen more similar to DDD
Business logic in services, handlers as pads, helpers are placed in separate folders.

Instruction:
(Makefile)

1. git clone https://github.com/v21kravets/golang-testing-task.git
2. cd golang-testing-task

3. (If GO is installed, then make run)
If not, you can use docker container

build the project on docker:
make build

close the project:
make down

endpoint: http://localhost:8080
