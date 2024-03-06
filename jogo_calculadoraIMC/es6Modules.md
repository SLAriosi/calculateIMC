# ES Modules
---

* Sintaxe que entrou no JS no EcmaScript 6 (ES6)

* Disponibilizar qualquer tipo de dado entre arquivos

* Separar código em diversos arquivos

* Isolar escopo e código

___

# Preparando o ambiente para usar ES Modules
___

* Numa nova pasta, vamos criar os arquivos:

>index.html, main.js, utils.js


* Prepare o index.html

>Crie a estrutura e adicione o main.js <script>

* Habilite a tag <script> para utilizar a sintaxe

>adicionaremos o atributo type="module" à tag script

...
// para usar, precisamos adicionar o atributo
// type="module" no nosso script principal
<script src="main.js" type="module" ></script>
...