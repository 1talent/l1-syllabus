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
- Complete `auth` handlers

## Session 6: Setup Persistance layer (1)

- Overview persistance layer infrastructure: `postgres`, `integresql` containers
- Overview persistance layer tech stack: `pq`, `sqlboiler`, `sql-migrate`
- Setup to call first `sqlboiler` (start with `users` model)

## Session 7: Setup Persistance layer (2)

- How to use `sql-migrate`, `sqlboiler`
- Integrates `pgFormatter` and `vscode-pgFormatter` for SQL formatting
- Complete `users` model

## Session 8: Complete Users models & Authentication feature

- Complete `app_user_profiles`, `access_token`, `refresh_tokens` models
- Integrate above models with `auth` handlers
- Test results

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
