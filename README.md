# umami

## What This Is

A practical reference entry for product and engineering: the umami notes, examples and fixes we reach for repeatedly. Kept current as part of the wider Swift Tech Co. engineering library.

## Images

[![umami](images/preview.png)](https://github.com/Swift-Tech-Co/umami)

## 🚀 Getting Started

A detailed getting started guide can be found at umami.is/docs.

---

## 🛠 Installing from Source

### Requirements

- A server with Node.js version 18.18+.
- A PostgreSQL database version v12.14+.

### Get the source code and install packages

```bash
git clone https://github.com/Swift-Tech-Co/umami
cd umami
pnpm install
```

### Configure Umami

Create an `.env` file with the following:

```bash
DATABASE_URL=connection-url
```

Optional: set `API_URL` to change the base URL used by internal UI API calls.
Relative paths are served under `BASE_PATH`; absolute URLs are proxied through the local `/api` route.
For example, `API_URL=/internal-api` or `API_URL=https://github.com/Swift-Tech-Co/umami

Optional: set `TWO_FACTOR_ENCRYPTION_KEY` to a 64-character hex string to enable two-factor
authentication. Generate one with `openssl rand -hex 32`. Two-factor authentication is unavailable
and cannot be required until this key is set.

MCP is disabled by default. Set `MCP_ENABLED=1` to enable the `/mcp` endpoint, then
authenticate with an API key generated under Settings → API keys.

The connection URL format:

```bash
postgresql://username:mypassword@localhost:5432/mydb
```

### Build the Application

```bash
pnpm run build
```

The build step will create tables in your database if you are installing for the first time. It will also create a login user with username **admin** and password **umami**.

### Start the Application

```bash
pnpm run start
```

By default, this will launch the application on `https://github.com/Swift-Tech-Co/umami You will need to either proxy requests from your web server or change the port to serve the application directly.

---

## 🐳 Installing with Docker

Umami provides Docker images as well as a Docker compose file for easy deployment.

Docker image:

```bash
docker pull docker.umami.is/umami-software/umami:latest
```

Docker compose (Runs Umami with a PostgreSQL database):

```bash
docker compose up -d
```

---

## 🔄 Getting Updates

To get the latest features, simply do a pull, install any new dependencies, and rebuild:

```bash
git pull
pnpm install
pnpm build
```

To update the Docker image, simply pull the new images and rebuild:

```bash
docker compose pull
docker compose up --force-recreate -d
```

---

## 🛟 Support

<p align="center">
  <a href="https://github.com/Swift-Tech-Co/umami"></a>
  <a href="https://github.com/Swift-Tech-Co/umami"></a>
  <a href="https://github.com/Swift-Tech-Co/umami"></a>
</p>

[release-shield]: https://github.com/Swift-Tech-Co/umami
[releases-url]: https://github.com/Swift-Tech-Co/umami
[license-shield]: https://github.com/Swift-Tech-Co/umami
[license-url]: https://github.com/Swift-Tech-Co/umami
[build-shield]: https://github.com/Swift-Tech-Co/umami
[build-url]: https://github.com/Swift-Tech-Co/umami
[github-shield]: https://github.com/Swift-Tech-Co/umami
[github-url]: https://github.com/Swift-Tech-Co/umami
[linkedin-shield]: https://github.com/Swift-Tech-Co/umami
[linkedin-url]: https://github.com/Swift-Tech-Co/umami
[telegram-shield]: https://github.com/Swift-Tech-Co/umami
[telegram-url]: https://t.me/+Qt_eFvkb2rliMzNh

---

## Swift Tech Co.

Built and maintained by Swift Tech Co.

AI Automation | FinTech Platforms | Custom Software and Mobile Apps | SaaS Platforms | Cloud Infrastructure | Cybersecurity | SEO and Marketing | API Integration

**Join our community on Telegram:** [t.me/+Qt_eFvkb2rliMzNh](https://t.me/+Qt_eFvkb2rliMzNh)

Home | Services | Careers | Referral Program | Influencers | About | Contact

**Connect**

- Website: https://github.com/Swift-Tech-Co/umami
- LinkedIn: [linkedin.com/in/stephenoladoke](https://www.linkedin.com/in/stephenoladoke/)
- LinkedIn (Company): [linkedin.com/company/swift-tech-co](https://www.linkedin.com/company/swift-tech-co)
- X: [@MrOladoke](https://x.com/MrOladoke)
- Instagram: [@mr.oladoke](https://www.instagram.com/mr.oladoke/)
- Organization: [github.com/Swift-Tech-Co](https://github.com/Swift-Tech-Co)

## Sources

Compiled and maintained from upstream [umami-software/umami](https://github.com/umami-software/umami) under permissive open-source license.

---

Maintained by [Swift Tech Co.](https://github.com/Swift-Tech-Co) - [Telegram](https://t.me/+Qt_eFvkb2rliMzNh)

## Sources

Compiled and maintained from upstream [umami-software/umami](https://github.com/umami-software/umami) under permissive open-source license.

---

Maintained by [Swift Tech Co.](https://github.com/Swift-Tech-Co) - [Telegram](https://t.me/+Qt_eFvkb2rliMzNh)

## Sources

Compiled and maintained from upstream [umami-software/umami](https://github.com/umami-software/umami) under permissive open-source license.

---

Maintained by [Swift Tech Co.](https://github.com/Swift-Tech-Co) - [Telegram](https://t.me/+Qt_eFvkb2rliMzNh)

## Sources

Compiled and maintained from upstream [umami-software/umami](https://github.com/umami-software/umami) under permissive open-source license.

---

Maintained by [Swift Tech Co.](https://github.com/Swift-Tech-Co) - [Telegram](https://t.me/+Qt_eFvkb2rliMzNh)