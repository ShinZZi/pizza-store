
# Pizza Delivery Application developed using MERN stack.



## Features

- Add to cart
- Update cart
- Delete cart
- User Authentication
- Stripe payment integration
- Placing Orders
- Storing and retrieving data


## API Reference

#### User

```http
  POST /api/users/register
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `name` | `string` | **Required** |
| `email` | `string` | **Required** |
| `password` | `string` | **Required** |


```http
  POST /api/users/login
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `email` | `string` | **Required** |
| `password` | `string` | **Required** |

```http
  POST /api/users/deleteuser
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `userid` | `string` | **Required**. The id of user|

#### Check for more . . .


## Environment Variables

To run this project, you will need to follow this intruction

- Create .env file in root folder and add these Variables
  
  `DB_URI`- The database link of mongoDB

  `SECRET_KEY` - Secret key of stripe payment API

- Create .env.client in client folder and add these Variables

  `REACT_APP_PUBLISH_KEY` - Publish key of stripe payment API


## Demo Card

Card Number: 4242 4242 4242 4242

Date: Any future date

CVC: Any 3 digits

For more information, check [this](https://stripe.com/docs/testing)