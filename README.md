# Broker


GET /stocks/msft
{
    price: 123.12 
}

POST /stocks/msft/sell
{
    uuid: 12332189
    quantity: 10
    price: 123.12 
}

POST /broker/msft/buy
{
    quantity: 10
    price: 123.12 
}

Background job / task runner:



# Installation Guide

brew update
brew install pyenv

create virtual-env
source env/bin/activate

pipenv install pipenv
pipenv install pytest
pipenv install flask

docker-compose up -d

** documentation missing (swagger?)


