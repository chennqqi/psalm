# MixedInferredReturnType

Emitted when Psalm cannot determine a function's return type

```php
function foo() : int {
    return $_GET['foo'];
}
```