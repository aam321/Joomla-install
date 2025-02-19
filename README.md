# Установка Joomla CMS с использованием Ansible

## Требования
- Ubuntu 20.04 или выше
- Ansible 2.9 или выше

## Установка
1. Скачайте файлы из репозитория:
   git clone https://github.com/aam321/Joomla-install.git
2. cd joomla-ansible
3. Запустите плейбук:
 ansible-playbook -i inventory site.yml --ask-vault-pass
4. После завершения установки, откройте браузер и перейдите по адресу вашего сервера для завершения настройки Joomla


