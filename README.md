## Get users:
Get http://localhost:3001/users 

## Create account: 
Post http://localhost:3001/register
{
	"email": "kenzinho@mail.com",
	"password": "123456",
	"name": "Kenzinho",
	"age": 38,
}

## Login: 
Post http://localhost:3001/login
{
	"email": "abcd@abcd.com",
	"password": "123456"
}

## New pokemon: 
Post http://localhost:3001/pokemon 
Authorization: Bearer 
{
	"type": "fairy",
	"name": "gardevoir",
	"userId": 2
}

## Get all pokemons: 
Get http://localhost:3001/pokemon

## Set level: 
Post http://localhost:3001/level,
Authorization: Bearer 
{
	"level": 550,
	"userId": 2
}

## View level: 
Post http://localhost:3001/level,
Authorization: Bearer 