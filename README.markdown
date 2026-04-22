# Blog

Este blog tem como propóto registrar e armazenar meus estudos. Pretendo manter por aqui os livros, materias didáticos e itens relevantes da graduação. 

Sinto que vai melhorar minha boa prática mais do que o Notion. 

## Como criar um blog igual esse?

O passo a passo que utilizei para a criação desse blog foi bem simples, **tudo via terminal mesmo**. 

Minha configuração é Ubuntu então o guia vai ser com base nesse sistema operacional

1. Comecei com a instalação do Ruby, na versão mais nova, porém se quiser outra ela deve ser acima da 2.5

```bash 
sudo apt install ruby 
```

2. Instalçao do Gem e Bundler
```bash 
gem install jekyll bundler
```

3. Confirme se deu tudo certinho 

``` bash 
ruby -v
jekyll -v
```
4. Criando o projeto 

É importante escolher a pasta que deseja criar o projeto pra ficar todo organizado, use ls e cd para se encontrar 

```bash 
jekyll new o-nome-que-quiser
cd o-nome-que-quiser
```

5. Subindo `localmente` para testes
```bash 
bundle exec jekyll serve
```

E pronto! Só é clicar no link gerado
```bash
Server address: http://127.0.0.1:4000/
```

Que abrirá no seu navegador!



