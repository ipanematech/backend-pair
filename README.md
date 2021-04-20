# Code Challenge

```
docker-compose build
docker-compose run app bundle install
docker-compose run app rails db:drop db:create db:migrate
docker-compose run app yarn install
```

1. Create an endpoint to persist a product with the following attributes: name, price and type
2. We have two possible type of products: national product and international product
3. For international products we should add 50% of taxes in the price, so the price will increase 50%.
4. For national products the price should be price - 10.
4. What if you need to add 10 new types of products with 10 different business rules?
