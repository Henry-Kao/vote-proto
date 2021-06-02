# guideline

## simple guides

1. message name should use pascal case like `GetUserCommand`
2. field name should use snake case like `user_name`
3. repeated field name should use pluralized style like `user_ids`
4. enum name should use pascal case like `ChatType`
5. enum field should use all caps snake case like `CHAT_TYPE_GROUP`
6. service name should use pascal case like `GroupService`
7. int64 fields should add annotaion `[jstype=JS_STRING]` to tail for pitiful javascript
8. empty command or result should use google empty struct `google.protobuf.Empty`

## references

- [Google Style Guide](https://developers.google.com/protocol-buffers/docs/style)