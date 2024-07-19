# Домашнее задание к занятию «`Безопасность в облачных провайдерах`» - `Живарев Игорь`

Используя конфигурации, выполненные в рамках предыдущих домашних заданий, нужно добавить возможность шифрования бакета.

---
## Задание 1. Yandex Cloud   

1. С помощью ключа в KMS необходимо зашифровать содержимое бакета:

 - создать ключ в KMS;
 - с помощью ключа зашифровать содержимое бакета, созданного ранее.


Resource Terraform:

- [IAM Role](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role).
- [AWS KMS](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/kms_key).
- [S3 encrypt with KMS key](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/s3_bucket_object#encrypting-with-kms-key).



### Правила приёма работы

Домашняя работа оформляется в своём Git репозитории в файле README.md. Выполненное домашнее задание пришлите ссылкой на .md-файл в вашем репозитории.
Файл README.md должен содержать скриншоты вывода необходимых команд, а также скриншоты результатов.
Репозиторий должен содержать тексты манифестов или ссылки на них в файле README.md.

------


## Ответ

### Задание 1.


Завершения работы комманды `terraform apply` и ссылка на `bucket`
![cli](img/cloud-03_01.png)


Попытка перейти по ссылке в браузере
![browser](img/cloud-03_02.png)


Созданный ключ _encryption-key_ в косоли Яндекс.Облака
![key](img/cloud-03_03.png)


Загруженный файл с картинкой в `bucket` в косоли Яндекс.Облака
![picture](img/cloud-03_04.png)

------