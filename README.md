## CloudFormation
Just incorporating some CF samples I have created

On s3.yaml and using `Atom` with a helper, I noted the following had to be commented out just to pass  
`aws cloudformation validate-template --template-body file://<some path>/s3.yaml`

```
# Parameters:

# Mappings:

# Conditions:
```

I am assuming a simple `index.html` and `error.html`
