## Fuma Lofi

Some nice lofi music and a music player.

**Demo:** https://lofi.crack.dev

![Preview](./public/preview.png)

### Run on local

Clone the repository.

```bash
git clone https://github.com/n0lawz/cracked-lofi
```

Install with [pnpm](https://pnpm.io).

```bash
pnpm i
```

Run in development mode.

```bash
pnpm dev
```

#### Add Songs

Put your songs in the `./public` folder, and run `pnpm run generate:music` to sync songs data with web player.

#### Build

This project uses Vite and React.js.

```bash
pnpm build && pnpm preview
```

