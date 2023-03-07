# woocommerce
wooCommerce Go REST API Library

[WooCommerce API Doc](https://woocommerce.github.io/woocommerce-rest-api-docs/#)

fork by https://github.com/chenyangguang/woocommerce

## Install

```console
 go get github.com/ranjiaming/woocommerce_golang_sdk
```

## updateNote
1. 订单字段DiscountsTotal从woocommerce返回两种数据类型，分别是：int和string，这里将字段设置为json.RawMessage类型。（2023-03-07）