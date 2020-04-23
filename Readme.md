1. Executable:

First and unique time setup:

`sh install.sh`

Run to export the alias: 

```
alias python-custom=`pwd`/main
```


2. Development:

Activate the enviroment:

`source lib/bin/activate`

Install packages:

`pip install -r requirements.txt`

Install any package:

`pip install <package>`

Remember to keep the requirements.txt updated:

Add packages to it, look for the specific version that you are using:
`pip freeze`