# BriefCase : A deShare Platform
![Screenshot (13)](https://github.com/nishant-Tiwari24/briefcase/assets/72213961/5b55af63-f855-4a85-978d-53a3b52a1d10)

## Getting Started

+ Clone the repository

      git clone https://github.com/nishant-Tiwari24/briefcase.git

+ Install IPFS Desktop Client

+ install necessary packages for client

      cd client
      yarn

+ Install necessary packages for server

      cd server
      yarn

+ Install necessary packages for blockchain

      cd blockchain
      yarn

+ running the project
      Make sure to run the IPFS desktop client

      cd client
      yarn dev
      


{
  "name": "client",
  "private": true,
  "version": "0.0.0",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview",
    "deploy": "yarn build && npx thirdweb@latest upload dist"
  },
  "dependencies": {
    "@thirdweb-dev/chains": "^0.1.90",
    "@thirdweb-dev/react": "^4",
    "@thirdweb-dev/sdk": "^4",
    "@tremor/react": "^3.15.0",
    "@types/react": "^18.2.74",
    "axios": "^1.6.8",
    "crypto-js": "^4.2.0",
    "ethereumjs-util": "^7.1.5",
    "ethers": "^5",
    "multicoin-address-validator": "^0.5.16",
    "react": "^18.2",
    "react-datepicker": "^6.9.0",
    "react-dom": "^18.2",
    "react-icons": "^5.0.1",
    "react-just-parallax": "^3.1.16",
    "react-router-dom": "^6.22.3",
    "react-simple-chatbot": "^0.6.1",
    "react-split": "^2.0.14",
    "scroll-lock": "^2.1.5",
    "socket.io-client": "^4.7.5",
    "thirdweb": "^5.3.1",
    "wallet-address-validator": "^0.2.4",
    "web3": "^4.7.0"
  },
  "devDependencies": {
    "@types/react-dom": "^18.2.24",
    "@vitejs/plugin-react": "^2",
    "autoprefixer": "^10.4.19",
    "eslint": "^8.57.0",
    "eslint-plugin-react": "^7.34.1",
    "eslint-plugin-react-hooks": "^4.6.0",
    "eslint-plugin-react-refresh": "^0.4.6",
    "postcss": "^8.4.38",
    "tailwindcss": "^3.4.3",
    "vite": "^3",
    "vite-plugin-node-polyfills": "^0.7.0"
  },
  "main": "index.js",
  "license": "MIT"
}
