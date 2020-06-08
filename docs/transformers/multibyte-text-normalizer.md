<span style="float:right;"><a href="https://github.com/RubixML/RubixML/blob/master/src/Transformers/MultibyteTextNormalizer.php">[source]</a></span>

# Multibyte Text Normalizer
This transformer converts all [multibyte text](https://www.php.net/manual/en/intro.mbstring.php) to lowercase and removes extra whitespace. Multibyte strings contain characters such as accents (é, è, à), emojis (😀, 😉) or characters of non roman alphabets such as Chinese and Cyrillic.

> **Note:** ⚠️ We recommend you install the [mbstring extension](https://www.php.net/manual/en/book.mbstring.php) for best performance.
 
**Interfaces:** [Transformer](api.md#transformer)

**Data Type Compatibility:** Categorical

## Parameters
This transformer does not have any parameters.

## Additional Methods
This transformer does not have any additional methods.

## Example
```php
use Rubix\ML\Transformers\MultibyteTextNormalizer;

$transformer = new MultibyteTextNormalizer();
```