# inAppPurchase

> Zakupy w aplikacji w Mac App Store.

Proces: [Main](../glossary.md#main-process)

## Zdarzenia

Moduł `inAppPurchase` emituje następujące zdarzenia:

### Zdarzenie: 'transactions-updated'

Wyemitowane, gdy jedna lub więcej transakcji zostało zaktualizowanych.

Zwraca:

* `event` Event
* `transactions` Transaction[] - Array of [`Transaction`](structures/transaction.md) objects.

## Metody

Moduł `inAppPurchase` ma następujące metody:

### `inAppPurchase.purchaseProduct(productID, quantity, callback)`

* `productID` String - The identifiers of the product to purchase. (The identifier of `com.example.app.product1` is `product1`).
* `quantity` Integer (optional) - The number of items the user wants to purchase.
* `callback` Function (optional) - The callback called when the payment is added to the PaymentQueue.
  * `isProductValid` Boolean - Sprawdź, czy produkt jest prawidłowy i czy został dodany do kolejki płatności.

You should listen for the `transactions-updated` event as soon as possible and certainly before you call `purchaseProduct`.

**[Deprecated Soon](modernization/promisification.md)**

### `inAppPurchase.purchaseProduct(productID, quantity)`

* `productID` String - The identifiers of the product to purchase. (The identifier of `com.example.app.product1` is `product1`).
* `quantity` Integer (optional) - The number of items the user wants to purchase.

Returns `Promise<Boolean>` - Returns `true` if the product is valid and added to the payment queue.

You should listen for the `transactions-updated` event as soon as possible and certainly before you call `purchaseProduct`.

### `inAppPurchase.getProducts(productIDs, callback)`

* `productIDs` String[] - The identifiers of the products to get.
* `callback` Function - The callback called with the products or an empty array if the products don't exist.
  * `products` Product[] - Array of [`Product`](structures/product.md) objects

Retrieves the product descriptions.

**[Deprecated Soon](modernization/promisification.md)**

### `inAppPurchase.getProducts(productIDs)`

* `productIDs` String[] - The identifiers of the products to get.

Returns `Promise<Product[]>` - Resolves with an array of [`Product`](structures/product.md) objects.

Retrieves the product descriptions.

### `inAppPurchase.canMakePayments()`

Zwraca wartość `Boolean`, niezależnie od tego, czy użytkownik może dokonać płatności.

### `inAppPurchase.getReceiptURL()`

Zwraca `String`, ścieżkę do paragonu.

### `inAppPurchase.finishAllTransactions()`

Completes all pending transactions.

### `inAppPurchase.finishTransactionByDate(date)`

* `date` String - The ISO formatted date of the transaction to finish.

Completes the pending transactions corresponding to the date.
