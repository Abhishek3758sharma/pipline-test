# pipline-test
@"
.terraform/
*.tfstate
*.tfstate.
*.tfvars.json
crash.log
crash.*.log
"@ | Out-File -Encoding utf8 .gitignore