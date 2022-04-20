# flat-cfn-param-tags
Represent a JSON array of key values into an AWS CLI suitable string (string can be used as argument for parameter and tags interpolation)

From a JSON representation as the below 
```json
[
 { "Key": "Key1", "Value":"Value1"}, { "Key": "Key2", "Value":"Value2"}
]
```

```sh
# Flat to string comma separated
python flat-json-tags.pyc PATH_TO_YOUR_JSON_TAGS_FILE.json

# produces
Key1=Value1,Key2=Value2....

```
