# Tauri SvelteKit 4 TeamIT
<img width="1316" alt="Screenshot 2024-04-23 at 22 42 16" src="https://github.com/teamitfi/tauri-svelte-example/assets/8963529/706bd3ed-6038-478f-90e7-f56d79ba3fb3">

- **Tauri**
- **SvelteKit**
- **GitHub action** for cross-platform builds
- **TypeScript**
- **Preprocessing** with Sass installed by default
- **ESLint**
- **Prettier**

## Dev instructions

### Get started

1. Install Node.js
2. Install Rust
3. Follow the [Tauri setup guide](https://tauri.app/v1/guides/getting-started/setup)
4. Run `npm install`


### Commands
- `npm run dev`: Start app in dev mode
- `npm run build`: Build the app to a native executable
- `npm run lint`: Lint
- `npm run format`: Format

### Release new version
1. Update `CHANGELOG.md`
2. Bump the version number in `src-tauri/Cargo.toml`
3. Run `cargo check` to update `Cargo.lock`
4. Create a git tag in the format `v#.#.#`
5. Add release notes to the generated GitHub release and publish it
