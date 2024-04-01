# 20210716test
test



sequenceDiagram
    participant 実店舗
    participant ECサイト
    actor ユーザー

    ユーザー->>ECサイト: 商品を注文する
    ECサイト->>実店舗: 商品を発注する
    実店舗->>ユーザー: 商品を配送
    ユーザー->>ECサイト: 料金を払う
    ECサイト->>実店舗: 料金の一部を渡す
