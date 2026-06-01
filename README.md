# set-pom-parent-version-action
Surgically updates `<parent><version>` and root `<version>` in a `pom.xml` using Python regex.

## Usage
```yaml
- uses: arvato-systems-jacs/set-pom-parent-version-action@master
  with:
    pom_path: 'pom.xml'
    parent_version: '9.1.26'
    project_version: '9.1.5'
```
