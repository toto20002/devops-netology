Игнорирование касается только папки /Terraform т.к. файил размещен именно в нём.

**/.terraform/* - Игнорируются все файлы, которые содержатся в папке .terraform, в том числе и внутри подкаталогов

*.tfstate и *.tfstate.* - Игнорируются файлы заканчивающиеся на  .tfstate и файлы с частью наименования .tfstate с продолжением.

crash.log - Игнорирует файл crash.log

*.tfvars - Игнорируются файл заканчивающиеся на .tfvars

override.tf - Игнорирует один файл override.tf

override.tf.json - Игнорирует один файл override.tf.json

*_override.tf - Игнорируются файл заканчивающиеся на _override.tf

*_override.tf.json    - Игнорируются файл заканчивающиеся на *_override.tf.json

.terraformrc  - Игнорирует один файл .terraformrc

terraform.rc  - Игнорирует один файл terraform.rc


------------------
Новая строка
