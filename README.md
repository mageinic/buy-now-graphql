# Buy Now GraphQL

**Buy Now GraphQL is a part of MageINIC Buy Now extension that adds GraphQL features.** This extension extends Customer Profile definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/buy-now-graphql

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Buy Now GraphQL requires installing [MageINIC Buy Now](https://github.com/mageinic/Buy-Now) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/buy-now
```

## 2. How to use

- To view the queries that the **MageINIC Buy Now GraphQL** extension supports, you can check `Buy Now GraphQl User Guide.pdf` Or run `BuyNowGraphQl.postman_collection.json` in Postman.

## 3. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
