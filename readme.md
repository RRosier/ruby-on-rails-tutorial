1. Clone repo
2. Open in VS Code
3. Run Dev Containers
> Dev Container: Reopen in Container
    Configure Docker Desktop
    Docker --> Configuretion --> Resources --> WSL integration --> Enable Ubuntu
4. Install dependencies (in dev container terminal)
``` bash
cd blog
bundle install --gemfile Gemfile
```
5. Call migrations to create DB
``` bash
bin/rails db:migrate
```