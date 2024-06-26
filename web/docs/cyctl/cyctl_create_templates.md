# cyctl create templates

Create template

### Synopsis

The create template command allows you to create templatestore from the Cyclops API.

```
cyctl create templates NAME --repo=repo --path=path --version=version [flags]
```

### Examples

```
# Create template
cyctl create template NAME --repo='github.com/repo/a' --path='/path/to/charts'

# Create template sample command
cyctl create template NAME --repo='https://github.com/cyclops-ui/templates' --path='/path' --version='main'
```

### Options

```
  -h, --help               help for templates
  -n, --namespace string   Namespace where the template will be created (default "cyclops")
  -p, --path string        Path to the charts in the repository
  -r, --repo string        Repository URL of the template
  -v, --version string     Version of the template
```

### SEE ALSO

* [cyctl create](cyctl_create.md)	 - Create custom resources like modules, templates, and templateauthrules

###### Auto generated by spf13/cobra on 24-Jun-2024