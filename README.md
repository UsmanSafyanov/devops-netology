new project

in folder "/terraform/.gitignore" will be ignored:
1) Local .terraform directories
2) .tfstate files
3) Crash log files
4) all .tfvars files, which are likely to contain sentitive data, such as
password, private keys, and other secrets. These should not be part of version control as they are data points which are potentially sensitive and subject to change depending on the environment
5) override files as they are usually used to override resources locally and so are not checked in
6) Include override files you do wish to add to version control using negated pattern
7) Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
new line
