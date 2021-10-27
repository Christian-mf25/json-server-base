## Get users:
Get https://kenziemon.herokuapp.com/users

## Create account: 
Post https://kenziemon.herokuapp.com/register
{
	"email": "kenzinho@mail.com",
	"password": "123456",
	"name": "Kenzinho",
	"age": 38,
}

## Login: 
Post https://kenziemon.herokuapp.com/login
{
	"email": "abcd@abcd.com",
	"password": "123456"
}

## New pokemon: 
Post https://kenziemon.herokuapp.com/pokemon 
Authorization: Bearer 
{
	"type": "fairy",
	"name": "gardevoir",
	"userId": 2
}

## Get all pokemons: 
Get https://kenziemon.herokuapp.com/pokemon

## Set level: 
Post https://kenziemon.herokuapp.com/level,
Authorization: Bearer 
{
	"level": 550,
	"userId": 2
}

## View level: 
Post https://kenziemon.herokuapp.com/level,
Authorization: Bearer 