[comment]: # (Note: This documentation is generated dynamically in the build process.  To modify the contents, change the javadoc on the _invoke method of the BIF class)

# Function: `GetLocaleInfo`

Retrieves a struct containin info on a locale, with an optional display locale

## Method Signature
```
GetLocaleInfo(locale=[string], dspLocale=[string])
```
### Arguments

| Argument | Type | Required | Description | Default |
|----------|------|----------|-------------|---------|
| `locale` | `string` | `false` | Optional locale to retrieve information on - either a common format ( "German" ), or an ISO Directive |  |
| `dspLocale` | `string` | `false` | Optional display language locale |  |

## Examples

```
GetLocaleInfo(locale=[string], dspLocale=[string])
```

## Related
  * [GetLocale](./GetLocale.md)
  * [GetLocaleDisplayName](./GetLocaleDisplayName.md)
  * [LSCurrencyFormat](./LSCurrencyFormat.md)
  * [LSIsCurrency](./LSIsCurrency.md)
  * [LSIsNumeric](./LSIsNumeric.md)
  * [LSNumberFormat](./LSNumberFormat.md)
  * [LSParseCurrency](./LSParseCurrency.md)
  * [LSParseNumber](./LSParseNumber.md)
  * [SetLocale](./SetLocale.md)