# Statamic - Starter kit

The Statamic cms template makes it super easy to start a new project with a bunge of pre-defined settings. These settings are quite various and consist of fieldsets & blueprints, statamic settings, addons and many more.

## How to install

1. `statamic new {project_name} maartenvanhunsel/statamic-starter-kit`
2. Add submodule [by instructions](https://gitlab.com/ptchr-projects/statamic-basics).
3. `php artisan key:generate`
4. `cp .env.example .env`
5. `yarn install && yarn build`
6. `valet link {project_name}`
7. Navigate to `http://{project_name}/cp`

## What's inside?
See [statamic docs](https://nobears.atlassian.net/l/cp/PR0rD2YP) for more information.