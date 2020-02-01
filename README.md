# BLOG API

Blog personal

## Configuration

- Install docker

- Install ruby version: 2.6.3

- Clone the repository `git clone git@github.com:jgersain/blog-api.git`

- Move to proyect directory


- Database creation (user: admin, password: pass)

  - `$ docker pull postgres:latest`
  - `$ docker run --name postgres-blog -p 127.0.0.1:5432:5432 -d postgres:latest`
  - `$ docker exec -it postgres-blog psql -U postgres -c "create role admin with login superuser password 'pass'"`

- Exec `bundle install`

- Create database `rails db:setup` 

- How to run the test suite
