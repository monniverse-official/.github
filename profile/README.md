# Monniverse

![Monniverse Project](/Monniverse_1.svg)

Welcome to the Monniverse project! This Next.js web application leverages the Lens Protocol SDK and wagmi for seamless blockchain interactions.

## Getting Started

To install the necessary dependencies and run the development server, use the following commands:

```bash
npm install
npm run dev
```

Then, open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Project Structure

```bash
/public/characters       - Static page for Monniverse characters, imported from Webflow
/src/app/characters      - Rendering the characters page via iframe
/src/app/page.tsx        - Home page rendering the LoaderScreen component
/src/app/navigation      - The navigation menu
/src/app/user-portal     - User space with wallet connection, NFTs, and balance check via Opensea API (More features coming soon)
/src/app/mermaid-oracle  - Prediction platform using Lens Protocol SDK, wagmi, connectkit.
/mermaid-oracle - Hardhat project for the Mermaid Oracle
```

Explore the enchanting world of Monniverse, connect your wallet, manage your NFTs, and more. Stay tuned for exciting new features!
