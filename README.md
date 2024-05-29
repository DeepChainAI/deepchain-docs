# Limitless Knowledge Layer

This text updates the original README to indicate that the documentation is under development and includes an overview of the new sections related to LimitlessLedger and DeepChain.

These docs use the Material theme for MkDocs. 

Our goal is to provide a high-quality, comprehensive, and user-friendly source of truth for LimitlessLedger's technology, including our innovative AI-powered rollup solution, DeepChain.

- This documentation includes sections on:
- DeepChain Overview
- LimitlessLedger CDK Integration
- zkEVM
- Developer Tools
- Running Locally

## Run locally

### Prerequisites

1. [Python 3.12](https://www.python.org/downloads/).
2. [`virtualenv`](https://pypi.org/project/virtualenv/): Install using `pip3 install virtualenv`.

### Setup

1. Clone the repository.
2. `cd` to the root.
3. Run the `run.sh` script. You may need to make the script executable: `chmod +x run.sh`

```sh
./run.sh
```

The site comes up at http://127.0.0.1:8000/ 

### Docker 

If you prefer Docker, you can build and run the site using the following commands:

```sh
docker build -t polygon-docs .
docker compose up
```

## Contributing

### Getting started

1. **Fork and branch**: Fork the `main` branch into your own GitHub account. Create a feature branch for your changes.
2. **Make changes**: Implement your changes or additions in your feature branch.
3. **Contribution quality**: Ensure that your contributions are:
   - **Atomic**: Small, self-contained, logical updates are preferred.
   - **Well documented**: Use clear commit messages. Explain your changes in the pull request description.
   - **Tested**: Verify your changes do not break existing functionality.
   - **Styled correctly**: Follow the [Microsoft Style Guide](https://learn.microsoft.com/en-us/style-guide/welcome/).

### Creating a pull request

1. **Pull request**: Once your changes are complete, create a pull request against the main branch of Polygon Knowledge Layer.
2. **Review process**: Your pull request will be reviewed by the maintainers. They may request changes or clarifications.
3. **Responsibility**: Contributors are expected to maintain their contributions over time and update them as necessary to ensure continued accuracy and relevance.

### Best practices

- **Stay informed**: Keep up-to-date with the latest developments in Polygon technologies.
- **Engage with the community**: Participate in discussions and provide feedback on other contributions.
- **Stay consistent**: Ensure your contributions are coherent with the rest of the documentation and do not overlap or contradict existing content.

## Contact and support

- For docs issues (technical or language) open an issue here.
- For technical issues with the software, either raise an issue here and we will follow up, or check https://support.polygon.technology/support/home. 

