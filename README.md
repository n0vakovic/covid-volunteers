# covid-volunteers

This repository stores the code for the [http://pobedimokoronu.com](pobedimokoronu.com), Serbian localization of https://helpwithcovid.com/ website.

The stack is:
- ruby on rails
- tailwind css
- postgres 

# Running app locally

## Dependencies
- ruby `2.6.3`
- bundler `2.1.4`
- postgres

## Installation
Run the following commands:
- `bundle`
- `yarn install`

- Start postgres:
  - On mac, you can use `pg_ctl -D /usr/local/var/postgres start`
  - ( To stop postgres use `pg_ctl -D /usr/local/var/postgres stop` )

- `rake db:create && rake db:migrate`

## Launch app
- `rails server`
- Go to `http://localhost:3000` to view app

