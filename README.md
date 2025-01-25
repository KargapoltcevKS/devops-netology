# devops-netology

1 First line
* 2 two line 
* 3 3 line
* 4 4 linee
* 5

**/.terraform/*              # Игнорировать все файлы в директории .terraform/
*.tfstate                    # Игнорировать все файлы с расширением .tfstate
*.tfstate.*                  # Игнорировать все файлы c именем tfstate с любым расширением
crash.log                    # Игнорировать все файлы c именем crash и расшмрением log
crash.*.log                  # Игнорировать все файлы с именем crash и любым расширением
*.tfvars                     # Игнорировать все файлы с расширением tfvars
*.tfvars.json                # Игнорировать все файлы любые файлы с расширениями tfvars и json
override.tf                  # Игнорировать все файлы c имененм override и расширением tf
override.tf.json             # Игнорировать все файлы override с раширением tf и json
*_override.tf                # Игнорировать все файлы названия которых оканчиваются на _override и имеют расширение tf
*_override.tf.json           # Игнорировать все файлы названия которых оканчиваются на _override и имеют расширение tf или json
.terraform.tfstate.lock.info # Игнорировать все файлы c названиями terraform, tfstate, lock, info
.terraformrc                 # Игнорировать все файлы с расширением terraformrc
terraform.rc                 # Игнорировать все файлы terraform.rc

* THE AND
1
* 2