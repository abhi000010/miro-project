<a name="readme-top"></a>

# Miro Clone - Real-time collaboration, versatile canvas, rich media, secure.

<br />


1. Create `.env.local` file in **root** directory and paste .env.example file's content.

### 1. Convex Deployment Configuration:
- Navigate to the deployment settings section in your Convex account.
- Find the deployment details, including team and project names.
- Update the `CONVEX_DEPLOYMENT` variable in the `.env.local` file with the obtained information.

### 2. Clerk Authentication Keys:

- Find the section in your Clerk account related to API keys or authentication settings.

- Generate a pair of keys (Publishable Key and Secret Key).

- Replace the `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY` and `CLERK_SECRET_KEY` variables in the `.env.local` file with the keys obtained from Clerk.

### 3. Liveblocks API Keys:
- Navigate to your Liveblocks account settings or API keys section.

- Generate a pair of keys (Public Key and Secret Key) for development.

- Replace the `NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY` and `NEXT_PUBLIC_LIVEBLOCKS_SECRET_KEY` variables in the `.env.local` file with the Liveblocks API keys obtained.

### 4. Save and Secure:

1. Save the changes to the `.env.local` file.

2. Install Project Dependencies using `npm install --legacy-peer-deps` or `yarn install --legacy-peer-deps`.

3. Now  run `npm run dev`

4. Don't expose API keys and configuration values.

<br />
<p align="right">(<a href="#readme-top">back to top</a>)</p>
