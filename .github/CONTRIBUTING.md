# Contributing to VANTA Boutique

Thanks for your interest! VANTA Boutique is an open-source, cloud-native
microservices showcase, and contributions are welcome.

## How to contribute

1. **Fork** the repo and create a branch off `main`.
2. Make your change — keep commits focused; [conventional-commit](https://www.conventionalcommits.org/)
   messages are appreciated.
3. **Run the checks** for whatever you touched, e.g. for the reviews service:
   ```sh
   cd src/reviewsservice
   go vet ./... && go test ./...
   ```
4. Open a **pull request** describing what changed and why.

## Reporting bugs or ideas

Open a [GitHub issue](https://github.com/grvtech1/VANTA-Boutique/issues) with steps to
reproduce a bug, or a short description of a feature or idea.

## License

No CLA required. By contributing, you agree that your work is licensed under the
project's [Apache-2.0 license](/LICENSE).
