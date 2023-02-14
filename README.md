# Manhwa API templete


## Usage

1. Clone This Repository

```bash
git clone https://github.com/Aerysh/manhwaindo-api.git
```

2. Install Required Packages

```bash
npm install
```

or

```bash
yarn install
```

3. Start Application

```bash
npm run start
```

or using nodemon

```bash
npm run dev
```

## API Documentation

| Endpoint          | Params           | Description                  |
| ----------------- | ---------------- | ---------------------------- |
| /all/:page        | page             | Get All Manhwa List          |
| /latest           | -                | Get latest Manhwa Update     |
| /popular          |                  | Get Weekly Popular Manhwa    |
| /search/:title    | manhwa title     | Search Manhwa by Title       |
| /detail/:endpoint | manhwa endpoint  | Get Details About a Manhwa   |
| /read/:endpoint   | chapter endpoint | Get Images List Of a Chapter |
| /genre            | -                | Get All Genre                |
| /genre/:endpoint  | genre endpoint   | Get All Manhwa by Genre      |

## Todo

Checkout projects to see todo lists

## Contribution

All contribution are welcome, but please first discuss the change you wish to make via issue or any other method

## License

[GPL-3.0-or-later](https://github.com/Aerysh/manhwaindo-api/blob/master/LICENSE)
