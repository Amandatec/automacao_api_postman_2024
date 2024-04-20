# Projeto de Automação de API com Postman

Projeto de automação de API com Postman desenvolvido durante o academy do Qa.Coders pela Squad The Mentalist.

## Tecnologias utilizadas

- Postman web version

- node v16.18.0

- newman v6.0.0

- newman reporter-htmlextra

## Como instalar o ambiente

- Primeiro: instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)

- Segundo: realize a instalação do newman de forma global [baixe aqui a dependência](https://www.npmjs.com/package/newman)

```bash
npm install -g newman
```

- Terceiro: realize a instalação da dependência dos relatórios (opcional) 
 [baixe aqui](https://www.npmjs.com/package/newman-reporter-htmlextra)

```bash
npm install -g newman-reporter-htmlextra
```

## Como rodar os testes

### Pelo Postman web ou desktop

- Importe a collection e as variáveis de ambiente e globals

- Execute a seguinte linha de comando para rodar os testes

 ```bash
newman run user_postman_collection.json -e env-QaCoders.json -g env-globals.json -r cli
  ```

## Execução com Report html-extra (opcional)

```bash
newman run user_postman_collection.json -e env-QaCoders.json -g env-globals.json -r htmlextra
```

### Report

Se você optou por rodar os testes com o report htmlextra, você gerou um arquivo html com o resultado dos teses e para verificar as validações você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e environment se encontram.

## Entre em contato

 <a href="https://www.linkedin.com/in/amandaoliveira--/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" style="margin-right: 2vw" target="_blank"></a>
<a href="http://discordapp.com/users/Amandatec#4699" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a>
  <a href="https://www.instagram.com/amanda_almajor/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:amandatec.oliveira@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>

 Made by [**Amandatec**](https://www.linkedin.com/in/amandaoliveira--/))