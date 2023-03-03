# Django Project Instruction

## Project Stack

|  Name    	| Version  	| Name II    	| Version 	|
|----------	|----------	|------------	|---------	|
| Python   	| 3.11.1   	| Nginx      	|         	|
| Django   	| 4.1.6    	| Redis      	|         	|
| Ubunto   	| 20.10.14 	| RabbitMQ   	|         	|
| Docker   	| 20.04    	| Prometheus 	|         	|
| Git      	| 2.33     	| ELK        	|         	|
| Postgres 	| 14.3     	|            	|         	|

## Development Environment Configuration

## Clone Project

The first things to do is to clone the repository.

### Python Env Setup

create a virtual environment to install dependencies inside it and active it.

#### virtualenv package

Install Virtualenv package

```sh
pip install virtualenv --upgrade
```

Create Virtual Environment command is:

```sh
virtualenv .venv 
```

Activate virtual environment in window

```sh
.\.venv\Scripts\activate.bat
```

To install dependencies you can use below command:

```sh
pip install django
```
TO save all dependency versions always after installation use below command:

```sh
pip freeza > requirements.txt
```

To install all current dependencies on your environment:

```sh
pip install -r requirements.txt
```

