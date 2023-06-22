*Шифрование файла:*\
gpg --recipient ключ  --encrypt file.txt \
*Расшифровка файла:* \
gpg --output decryt.txt --decrypt secret.txt.gpg \
*Подпись файла:* \
gpg --output secretFile.txt.sig --detach-sig secretFile.txt \
*Проверка подписи:* \
gpg --verify secret.txt.sig secret.txt \
