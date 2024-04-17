# devops-netology
**/.terraform/* - исключаются всё, находящиеся в каталогах .terraform на любом уровне вложенности в директории terraform репозитория (т.к. файл gitignore находится в каталоге terraform репозитория)
*.tfstate - исключаются все файлы с расширением tfvars
*.tfstate.* - исключаются все файлы с расширением tfvars.* (* - любые символы)
crash.log - исключается файл crash.log
crash.*.log - исключаются все файлы с расширением *.log (* - любые символы)
*.tfvars - исключаются все файлы с расширением .tfvars 
*.tfvars.json - исключаются все файлы с расширением .tfvars.json
override.tf - исключается файл override.tf
override.tf.json - исключается файл override.tf.json
*_override.tf - исключаются все файлы с окончанием _override.tf 
*_override.tf.json - исключаются все файлы с окончанием _override.tf.json
.terraformrc - исключаются все файлы с расширением .terraformrc
terraform.rc - исключается файл terraform.rc
add new line
