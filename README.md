# maverick-dao


Setting it up locally

- You will need Rust installed to run the app locally. Instructions to Install Rust are [here](https://www.rust-lang.org/tools/install)
- The app runs on [mdBooks](https://rust-lang.github.io/mdBook/)

- If you have anything setup correctly simply run `mdbook serve` to get the app running on https://localhost:3000 in watch mode. 

- The app deploys on Cloudflare pages which at the moment doesnt have support to run MDBook as part of the build process, hence we have to build it locally and push the built assests in the `/book` folder as part of the commits. Hopefully we dont have to do this when Cloudflare beings to support Rust