
# DT APi Documentation For Nudge

A nodejs-express api for perform crud operation of Nudge



## API Reference

#### Create a Nudge

```http
  POST /api/nudge
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `type` | `string` | **Required**. Type of nudge |
| `title` | `string` | **Required**. Title of nudge |
| `image` | `file` | **Required**. image of nudge |
| `schedule` | `timestamp` | **Required**. date of nudge |
| `description` | `string` | **Required**. description of nudge |
| `icon` | `file` | **Required**. icon of nudge |
| `invitation` | `string` | **Required**. write invitation of nudge |

#### Update a Nudge

```http
  POST /api/nudge
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `id` | `string` | **Required**. id of nudge |
| `type` | `string` | **Required**. Type of nudge |
| `title` | `string` | **Required**. Title of nudge |
| `image` | `file` | **Required**. image of nudge |
| `schedule` | `timestamp` | **Required**. date of nudge |
| `description` | `string` | **Required**. description of nudge |
| `icon` | `file` | **Required**. icon of nudge |
| `invitation` | `string` | **Required**. write invitation of nudge |

#### Get  Nudge By id
```GET
  GET /api/nudge/<id>
```

#### Delete  Nudge By id
```Delete 
  DELETE /api/nudge/<id>
```

#### Get  Nudge
```GET
  GET /api/nudge?type=event&limit=10&page=1
```
