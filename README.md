# odileeds-graph

This project defines a graph of the data used to generate the ODI Leeds dashboard, website and other visualisations
(such as the sponsor summarys).

It's built in GraphQL, which means we have a type system defining the relationships between elements.

The data model is defined in the [GraphQL Schema](./schema.graphql).

There is also a visualisation in the Github pages.

## Building

Install the packages using your favourite package manager.

Build using `npm run build` (or `pnpm build`).

### `pnpm`

I like `pnpm` (which can be set up using `npm install --global pnpm`).

The `package-lock.json` file (created by `npm`) is committed, so you need to
additionally run `pnpm import` every time the `package-lock.log` file changes.
