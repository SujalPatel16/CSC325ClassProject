## Markdown Quality Assurance

To ensure only high-quality markdown files are pushed to the default branch of this repository, contributors should use the following tools:

### Vale

Vale is a customizable, command-line linting tool for prose. It helps enforce writing style guides and ensures consistency in markdown documentation.

#### Installation and Usage

1. Install Vale by following the instructions at [Vale's official site](https://vale.sh/).
2. Configure Vale by adding a `.vale.ini` file at the root of the repository with the required rules.
3. Run Vale before pushing changes:
   ```sh
   vale .
   ```

### markdownlint-cli

markdownlint-cli is a tool for checking markdown files against standard linting rules to maintain consistency and readability.

#### Installation and Usage

1. Install markdownlint-cli:
   ```sh
   npm install -g markdownlint-cli
   ```
2. Run markdownlint to check for issues:
   ```sh
   markdownlint '**/*.md'
   ```
3. Fix any issues found before committing and pushing changes.

By integrating these tools into your workflow, you can ensure that all markdown files meet quality standards before merging into the default branch.

