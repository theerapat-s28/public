# Public

## Public is a project that contain files that are not concerned about privacy for easy download via lionsublime.com with `wget` or `curl`.


#### Download command with `wget`

```shell
wget -O ${file_name} https://raw.githubusercontent.com/theerapat-s28/public/main/README.md
```
or
```shell
wget -O ${file_name} http://lionsublime.com/README.md
```
---
#### Encryption
- Install software
```shell
sudo dnf install gnupg
```
- Basic encrypted command
```shell
gpg --batch --output ${output_file_name} --passphrase ${password} --symmetric ${target_file_path}
```
- Basic decrypted command
```shell
gpg --batch --output ${output_file_name} --passphrase ${password} --decrypt ${target_file_path}
```
