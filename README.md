# Steps to Create a GitHub Workflow

**Step 1:** Sign up and log in to [GitHub.com](https://github.com).

**Step 2:** Create a new repository.

**Step 3:** In the repo, create a folder `.github/workflows`.

**Step 4:** In the folder, create a YAML file with a `.yml` or `.yaml` extension.

**Step 5:** Add the content of the workflow in the file as follows:

```yaml
name: Hello-world

on: push

jobs:
  hello-world_job:
    runs-on: ubuntu-latest
    
    steps:
      - name: my-hello-world
        run: echo "hello world"


##**Step 6:** Commit and push the changes.

**Step 7:** Go to the repository main page and click the “Actions” tab.

**Step 8:** Select the workflow from the left sidebar and check the logs and results.
