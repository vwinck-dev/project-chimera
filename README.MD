# *WIP* - THIS PROJECT IS A WORK IN PROGRESS - *WIP*

A Discord bot developed with [Node.js](https://nodejs.org/) and [discord.js](https://discord.js.org/).  
Currently in early development — no defined purpose yet.

---

## Technologies
- [Node.js](https://nodejs.org/)
- [discord.js](https://discord.js.org/)
- [dotenv](https://www.npmjs.com/package/dotenv)

---


## Setup

### 1. Clone the repository
```bash
git clone git@github.com:vwinck-dev/discord-bot.git
cd discord-bot
````

### 2. Install dependencies

```bash
npm install
```

### 3. Configure `.env`

Create a `.env` file in the root based on `.env.example`:

```env
DISCORD_TOKEN=your_token_here
CLIENT_ID=your_client_id_here
GUILD_ID=your_guild_id_here
```

> **Important:**
> Never share your `DISCORD_TOKEN`.
> If it leaks, regenerate it immediately at the [Discord Developer Portal](https://discord.com/developers/applications).

---

## Running the Bot

```bash
npm start
```

If everything is correct, you should see:

```
Bot connected as MyBot#1234
```


---

## Contributing

Contributions are always welcome! To keep the project organized, please follow these steps:

1. Fork the project.
2. Clone your fork and create a branch from `develop` for your feature:

   ```bash
   git checkout develop
   git pull origin develop
   git checkout -b feature/your-feature
   ```
3. Make your changes and commit them:

   ```bash
   git add .
   git commit -m "feat: add new feature"
   ```
4. **Rebase your branch onto the latest `develop`** before pushing:

   ```bash
   git fetch origin
   git rebase origin/develop
   ```
5. Push your branch to your fork:

   ```bash
   git push origin feature/your-feature
   ```
6. Open a Pull Request **from your branch to the main project's `develop` branch**.

> Always rebase your branch onto the latest `develop` to keep the history clean and avoid conflicts.

---

## License


This project is licensed under the [MIT License](LICENSE.md).