Axum for Backend Development

Building a Basic Blog

1. Postgres
2. Axum framework
3. ORM
4. Tokio
5. Serde
6. Serde JSON
7. UUID
8. Date
9. Chrono
10. Workspace

ORM

- Sea ORM
- sqlx
- Diesel ORM

Entities

- Post
- Author
- Comment
- Likes

Post

- Id
- Title
- Image
- Content
- Description
- Created At
- Category id
- Updated At
- Author Id

Author

- id
- Author Name

Comment

- ID

Error handling
HTTP Status Code
JSON Responses
Vectors and Hashmaps

- Docker

docker run -d \
 --name postgres-db \
 -e POSTGRES_USER=postgres \
 -e POSTGRES_PASSWORD=password \
 -e POSTGRES_DB=axum_server \
 -p 5432:5432 \
 -v postgres-data:/var/lib/postgresql/data \
 postgres:15

# Connection string

# postgres://postgres:password@localhost:5432/axum_server

mysql://user:password@host:port/db_name
