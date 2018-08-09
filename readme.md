# Reproduction for bug mulesoft/oas-raml-converter#43

Input: [api.raml](api.raml)  
Output: [api.oas.json](api.oas.json)

You can run the following to reproduce output

```
oas-raml-converter --from RAML --to OAS30 api.raml > api.oas.json
```