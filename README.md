# Deploy hardware to FPGAs using github actions
With sabana, developers can create CI/CD workflows to easily deploy hardware code to FPGAs.

## Getting started
1. Join our [waitlist](https://docs.sabana.io/) to get an account. You could ping us in our [discord](https://discord.gg/TwzbFDBFcm) community, in case we haven't get back to you soon.
2. Once you have installed and logged with the [sabana CLI](https://docs.sabana.io/get-started/installation), your credentials should be located in `~/.sabana/config.json`
3. Fork this repo, and create two secrets `SABANA_ACCESS_TOKEN` and `SABANA_ID_TOKEN` using the values from `~/.sabana/config.json`
4. Go to "Actions" tab in the forked repository and run `e2e.yml` workflow
5. After a few minutes, you should have built, deployed, and run a complete FPGA workflow from Github.
