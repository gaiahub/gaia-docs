

Variables can be used in Custom Tool Function with the $ prefix.

```javascript
$vars.<variable-name>
```

If variable type is Static, the value will be retrieved as it is. If variable type is Runtime, the value will be retrieved from .env file.

You can also override variable values in API overrideConfig using vars:

```json
{
	overrideConfig: {
		vars: {
			var1: 'abc'
		}
	}
}
```

Read more from [Flowise Docs](https://docs.flowiseai.com/using-flowise/variables)

