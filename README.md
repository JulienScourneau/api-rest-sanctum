# APIRest Sanctum

Make a simple API with Laravel Sanctum


## API Reference

#### Get all items

```javascript
  GET /api/products
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `/` | `/` | Public. Return list of all products|

#### Add new item

```javascript
  POST /api/products/
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `name`      | `string` | **Required**. Logged and Access Token |
| `description`      | `string` | **Required**. Logged and Access Token |
| `price`      | `string` | **Required**. Logged and Access Token |

#### Get item

```javascript
  GET /api/products/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | Public **Required**. Id of product to fetch |

#### Search specific item

```javascript
  GET /api/products/search/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | Public |

#### Search specific item

```javascript
  PUT /api/products/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Logged and Access Token  |
| `name`      | `string` | **Required**. Logged and Access Token |
| `description`      | `string` | **Required**. Logged and Access Token |
| `price`      | `string` | **Required**. Logged and Access Token |

```javascript
  DELETE /api/products/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Logged and Access Token. Id of product to delete.  |






