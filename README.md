# repo2md

Simple utility to generate a markdown document from files in a cloned Git repository.

### Features

> [!NOTE]
> - Each file has a markdown heading, defined by file depth in the repo.
> - Code contained in each file is in markdown code blocks.

> [!TIP] 
> Further file types to be excluded can be added at the top of the script.

## Usage

```
python3 repo2md --help

python3 repo2md --repo_path ~/Downloads/example_repo/ --md_file_path ~/Downloads/example.md
```

### TODO

> 1. Exclude more file types
> 2. Add contents
> 3. Classes etc.