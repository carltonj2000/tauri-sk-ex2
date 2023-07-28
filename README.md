# Tauri With Svelte Kit Example 2


## Code Creation

From:
https://tauri.app/v1/guides/getting-started/prerequisites

```bash
sudo apt update
sudo apt install libwebkit2gtk-4.0-dev \
    build-essential \
    curl \
    wget \
    file \
    libssl-dev \
    libgtk-3-dev \
    libayatana-appindicator3-dev \
    librsvg2-dev
# install rustup (aka rust installer)
rustup update

mkdir tauri-sk-ex2; cd tauri-sk-ex2
npm create svelete@latest # skeleton project, typescript, prettier
npm install --save-dev @sveltejs/adapter-static@next 
npm install --save-dev @tauri-apps/cli
npm run tauri init # set web assets at ../build , all else defaults
npm run tauri dev
# add tuari handler code
npm install @tauri-apps/api
```

## Code History

The code in this repository is based on The
[SvelteKit and Tauri: Blazing-Fast Desktop Applications](https://youtu.be/Dobwjx7_xT0)
video.
The video is someone just following the steps in the 
[Tauri Quicke Start](https://tauri.app/v1/guides/getting-started/setup/).
