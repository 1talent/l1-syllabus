# golang code mentoring on Wednesdays

## Session 1: Setup Tools & Environment

- Support apps: Discord, Live share
- Vscode, Golang, Docker
- Run first go app

## Session 2: Project layout & configurations of `go-starter`

- Introduce tech stack in `go-starter`
- Project's main components overview: `cmd`, `internal`
- Play with environment configurations using `goenv`, `viper`

## Session 3: Introduction Web development in Go

- Introduce `echo` framework
- Setup server entry, routes, handlers (start with `auth` routes)
- Explain `go-starter` web development workflow

## Session 4: Scaffolding

- Scaffold from `cobra` to `echo`
- Url handlers with `echo`

## Session 5: Complete Authentication HTTP apis

- Complete `auth` middleware
- Complete `auth` routes
- Run persistance layer infrastructure: `postgres` containers

## Session 6: Setup Persistance layer (1)

- Overview persistance layer tech stack: `pq`, `sqlboiler`, `sql-migrate`
- How to use `sql-migrate`, `sqlboiler`
- Setup to call first `sqlboiler` (start with `users` model)

## Session 7: Setup Persistance layer (2)

- How to use `go swagger` to generate payload for `auth` handlers
- Log capability with the `zerolog` library and customisations in log.go and context.go
- Create  `PostRegisterRoute` and its handler

## Session 8: Complete Users models & Authentication feature

- Complete `post_register`, `post_login`, `post_logout`, `get_userinfo` routes
- Implement test for code

## Session 9: Introduce Postgres integrate tests, logging

- Overview logging stack: `go-spew`, `zerolog`
- How to configure and use logger
- Overview `integresql-client-go` and how to implement, run test cases 

## Session 10: Complete other HTTP APIs (1)

- Overview other HTTP apis: `common`, `push`
- Setup SMTP feature with go module `email`, `google` & `mailhog` infrastructure
- Test mail workflows

## Session 11: Complete other HTTP APIs (2)

- Complete feature `push`
- Complete feature `common`
- Test results, setup swagger docs

## Session 12: Introduce `gotrue`

- Retrospective `go-starter` & introduce `gotrue`
- Setup `gotrue` project to run
- Understand `gotrue` project layout
- Build `gotrue` authenticate feature
