# NextAuth.js

This is a starter project for Next.js with authentication using [NextAuth.js](https://next-auth.js.org/)

## Getting Started

- clone this repo and `cd` into it
- run `npm install`
- Add `.env` file to the root of the project with the following content:

```bash
# You will find these values in your GitHub OAuth App settings in Developer Settings on GitHub (Client ID and client secret), you will need to create a new OAuth App
GITHUB_ID=YOUR_GITHUB_ID
GITHUB_SECRET=YOUR GITHUB SECRET

# ! Your NEXTAUTH_SECRET secret should be at least 32 characters long, not parakeet :)
NEXTAUTH_SECRET=parakeet
# ! Your NEXTAUTH_URL should be the URL of your site, change it in production
NEXTAUTH_URL=http://localhost:3000
```

> Note: If you are deploying to Vercel, the `NEXTAUTH_URL` env variable is not necessary

### Running the app

```bash
npm run dev
```

- Open [http://localhost:3000](http://localhost:3000) with your browser to see the result

> Note: NextAuth.js has many providers, you can find them [here](https://next-auth.js.org/configuration/providers)

## Providers

- [Email](https://next-auth.js.org/configuration/providers/email)
- [Credentials](https://next-auth.js.org/configuration/providers/credentials)
- [GitHub](https://next-auth.js.org/providers/github)
- [Google](https://next-auth.js.org/providers/google)
- [Apple](https://next-auth.js.org/providers/apple)
- [Facebook](https://next-auth.js.org/providers/facebook)
- [Discord](https://next-auth.js.org/providers/discord)
- [LinkedIn](https://next-auth.js.org/providers/linkedin)
- [More...](https://next-auth.js.org/configuration/providers/oauth#built-in-providers)

## Learn More

- [How to set up Providers](https://next-auth.js.org/configuration/providers/oauth#built-in-providers)
- [NextAuth.js Getting Starter](https://next-auth.js.org/getting-started/example)
