# Getting Started

## Prerequisites
Before starting this project make sure that you have installed all of these prerequisites on your local machine

- [Node.js](https://nodejs.org/en/download/)
- [npm](https://www.npmjs.com/get-npm) or [yarn](https://yarnpkg.com/getting-started/install) or [pnpm](https://pnpm.io/installation)
- [git](https://git-scm.com/downloads)


## Setting up the project

- Create the .env file in the root folder
- Add following variables with your data
    
    ```bash
    GOOGLE_ID=your_google_id
    GOOGLE_CLIENT_SECRET=your_google_client_secret
    MONGODB_URI=your_mongodb_connection_string
    NEXTAUTH_URL=http://localhost:3000
    NEXTAUTH_URL_INTERNAL=http://localhost:3000
    NEXTAUTH_SECRET=your next auth secret 
    
    ```

- Install the dependencies

    ```bash
    npm install
    # or
    yarn install
    # or
    pnpm install
    ```

- Finally, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Sneak peek of the app

![prompt home page](https://github.com/ramithperera/promptopia_project/assets/89182652/925901fd-3461-4bc4-8265-9e80d0b2a94d)
