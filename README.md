<h1 align="center">
  <br>
    <img src="https://i.imgur.com/d8QEHRb.png" alt="Tradução Magento 2 pt_BR" width="128" height="128" title="Tradução Magento 2 pt_BR"/> 
  <br>
  Tradução para Magento 2 em Português do Brasil (pt_BR)
  <br>
</h1>

<p align="center">  
  <a href="https://packagist.org/packages/tecsecret/m2_pt_br"><img src="https://img.shields.io/packagist/dt/tecsecret/m2_pt_br.svg" alt="Total Downloads"></a>
</p>

# Compatível

- Magento 2 Open Source
- Magento Commerce


# Instalação

## Via Composer 

Para instalar essa tradução via [Composer](https://getcomposer.org) você precisa usar o terminal do seu servidor.

```
composer require tecsecret/m2_pt_br
php bin/magento setup:static-content:deploy pt_BR -f
php bin/magento cache:clean
```

# Como Usar

Para começar a usar a tradução instalada vá em `Stores -> Configuration -> General -> General -> Locale options` e selecione em **Locale** a opção **Brazilian Portuguese (Brazil)**.


# Autores
Tradução original [Crowdin](https://crowdin.com/project/magento-2).
Adaptação e modificação [Dep. de Desenvolvimento Web - Grupo TecSecret](https://tecsecret.com.br)
Revisao [Nelsir Luterek]
