Cancel request
==============

**[⬆ back to readme](../../README.md)**

To cancel a signature request, you simply have to send a request with the `transactionId`.
```php
$this->requester->cancelTransaction($transactionId);
```