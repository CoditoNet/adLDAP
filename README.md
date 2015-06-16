# Important information

This is only fork of [adldap/adldap](https://github.com/adldap/adldap) with fixed `v4.0.4` tag: now contains `composer.json` and can be used as vendor. In your project's `composer.json` define something like this:

```javascript
"repositories": [
	{
		"type": "vcs",
		"url": "https://github.com/CoditoNet/adLDAP"
	}
],
"require": {
	"php": ">=5.3.2",
	"adldap/adLDAP": "4.0.4"
}
```