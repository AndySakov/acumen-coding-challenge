# Weather Monster

## Description

A solution to the [acumen digital coding task](https://docs.google.com/document/d/1O2Keh4GRGKtjP3ma73M8cOJDTjUi_XvDgWeiMWzoW-g/edit)

## Installation

Run the command below in the project root dir to download the app dependencies

```bash
npm install
```

## Running the app

- Copy the .env.example file to a .env file and populate as applicable with a postgresql db url

- Run the db migrations by running the following command in the root dir

```bash
  npx prisma migrate dev
```

- Run the app with one of the following commands in the root dir

```bash
# development
npm run start

# watch mode
npm run start:dev
```

## Test

```bash
# unit tests
 npm run test
```
