# aws-key-selector
AWS Credentials Selector on Shell


## Usage

1. Copy `rb` file, `aws-credentials-selector.rb`.

2. Add this alias `.bashrc` or `.zshrc`

```
alias awsev='ruby ~/ruby/aws-credentials-selector.rb'
```

3. Execute

```
eval `awsev :credentails-name`
```
