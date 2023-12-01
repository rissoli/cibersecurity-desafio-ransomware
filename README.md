# Santander Bootcamp Cibersegurança

## Projeto Prático: Criando um Ransomware com Python

### Ferramentas

- Kali Linux
- python
- vim
- cat

### Arquivo comum a ser criptografado

- Criar arquivo teste.txt: ``` vim teste.txt ```
  
- Verificando o conteudo do arquivo: ``` cat teste.txt ```

![image](https://github.com/rissoli/cibersecurity-desafio-ransomware/assets/40303079/30145af5-5dd7-417d-a430-beb79556b808)


### Criptografando com o encrypter.py

- Executar o encrypter.py: ``` python3 encrypter.py ```

![image](https://github.com/rissoli/cibersecurity-desafio-ransomware/assets/40303079/e8a9e48b-3f0c-421d-b265-a6717f821ee7)


### Arquivo criptografado

- Listando os arquivos da pasta: ``` ls ```

![image](https://github.com/rissoli/cibersecurity-desafio-ransomware/assets/40303079/219242ed-18d0-416e-ac85-7a8d806b5cae)


### Descriptografando com o decrypter.py

- Executar o decrypter.py: ``` python3 decrypter.py ```

![image](https://github.com/rissoli/cibersecurity-desafio-ransomware/assets/40303079/758406a1-05aa-4b50-9628-a55845d0d447)


### Arquivo descriptografado

- Listando os arquivos da pasta: ``` ls ```
- Verificando o conteudo do arquivo: ``` cat teste.txt ```

![image](https://github.com/rissoli/cibersecurity-desafio-ransomware/assets/40303079/bdedb993-b8b4-4fa2-a8b5-2b46064ea7ae)
