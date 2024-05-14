# repo2md

Simple utility to generate a markdown document from files in a cloned Git repository.

### Features

> [!NOTE]
> - Each file has a markdown heading, defined by file depth in the repo.
> - Code contained in each file is in markdown code blocks.

> [!TIP] 
> Any of below can be configured in `CONFIG` at the top of the script.
> - Exludes standard data types.
> - Ignores `.git` directory.
> - Ignores hidden files.

### TODO

> 1. `argparse`
> 2. Exclude more file types
> 3. Add contents
> 4. Classes etc.