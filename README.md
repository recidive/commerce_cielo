#Instalação
* Via Drush
  * `cd sites/SEUDOMINIO`
  * `drush dl commerce_cielo`
  * `composer install`
  * Este módulo acompanha 2 sub-módulos, são eles o **commerce_cielo_checkout** e **commerce_cielo_webservice**.
  No momente apenas o **commerce_cielo_checkout** está pronto para ser usado em produção.
    * `drush en -y commerce_cielo_checkout`
* Acesse `admin/commerce/config/cielo`, siga as instruções, informe os dados necessários e salve o formulário.

#Utilização
* **commerce_cielo_checkout** ( Redireciona o comprador para a Cielo )
  * [Clique aqui](http://developercielo.github.io/Checkout-Cielo/) para ler as instruções sobre como configurar o 
  backend da Cielo em modo de teste.
  * Acesse `admin/commerce/config/payment-methods/manage/commerce_payment_cielo_checkout/edit/3`, siga as instruções,
  informe os dados necessários e salve o formulário.

* **commerce_cielo_webservice** ( Coleta os dados do cartão no website do vendedor )
  * **NÃO ESTÁ PRONTO PARA SER USADO**
  * Procuro interessado em ser co-mantenedor
  * [Clique aqui](https://developercielo.github.io/Webservice-1.5) para ver o manual de integração
