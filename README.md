# Starter Nx Web Components with Storybook

## Create Nx Workspace with Web Components

```bash
npx create-nx-workspace@latest --preset=web-components

# Repository name: starter-nx-wc-storybook
# Application name: wcsb
# Default stylesheet format: CSS
# Enable distributed caching to make your cli faster: No
```

### Run Nx

```bash
npx nx serve wcsb
```

## Add Storybook

```bash
yarn add -D @nrwl/storybook
```

## Setup Storybook

```bash
npx nx g @nrwl/storybook:configuration wcsb

# What UI framework plugin should storybook use?: @storybook/web-components
# Configure a cypress e2e app to run against the storybook instance?: false
# Which Storybook builder do you want to use?: vite
``` 

### Run Storybook

```bash
npx nx storybook wcsb
```





