# My project BACKEND

- `npm start`

curl --location 'http://localhost:3000/api/auth/register' \
--header 'Content-Type: application/x-www-form-urlencoded' \
--data-urlencode 'lastName=bbbb' \
--data-urlencode 'firstName=aaaa' \
--data-urlencode 'email=aa@aa.com' \
--data-urlencode 'password=senha123' \
--data-urlencode 'type=admin'

curl --location 'http://localhost:3000/api/auth/login' \
--header 'Content-Type: application/x-www-form-urlencoded' \
--data-urlencode 'email=a@a.com' \
--data-urlencode 'password=senha123'

curl --location 'http://localhost:3000/api/todo' \
--header 'Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0OWEzZWY3MzMyMGVkNjJlODZmM2EyZCIsImVtYWlsIjoiYUBhLmNvbSIsInVzZXJuYW1lIjoiYWFhYWFhIiwiZmlyc3ROYW1lIjoiYWFhYSIsImxhc3ROYW1lIjoiYmJiYiIsImlhdCI6MTY4NzgzMDI4MiwiZXhwIjozMzgwODQ0NTY0fQ.S2atlkYJQD1b4E9keaIXHy_zh9U0k-zT7l4umAtQnKU' \
--header 'Content-Type: application/x-www-form-urlencoded' \
--data-urlencode 'title=okokok'

curl --location 'http://localhost:3000/api/todo' \
--header 'Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0OWEzZWY3MzMyMGVkNjJlODZmM2EyZCIsImVtYWlsIjoiYUBhLmNvbSIsInVzZXJuYW1lIjoiYWFhYWFhIiwiZmlyc3ROYW1lIjoiYWFhYSIsImxhc3ROYW1lIjoiYmJiYiIsImlhdCI6MTY4NzgzMDI4MiwiZXhwIjozMzgwODQ0NTY0fQ.S2atlkYJQD1b4E9keaIXHy_zh9U0k-zT7l4umAtQnKU'

curl --location --request DELETE 'http://localhost:3000/api/todo/649a48e3b101349773e2d24c' \
--header 'Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0OWEzZWY3MzMyMGVkNjJlODZmM2EyZCIsImVtYWlsIjoiYUBhLmNvbSIsInVzZXJuYW1lIjoiYWFhYWFhIiwiZmlyc3ROYW1lIjoiYWFhYSIsImxhc3ROYW1lIjoiYmJiYiIsImlhdCI6MTY4NzgzMDI4MiwiZXhwIjozMzgwODQ0NTY0fQ.S2atlkYJQD1b4E9keaIXHy_zh9U0k-zT7l4umAtQnKU'



