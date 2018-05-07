# graphql-schema-linter-duplicated-errors

Example of duplicated errors when using graphql-schema-linter

## Steps

1.  Instal [`graphql-schema-linter`](https://github.com/cjoudrey/graphql-schema-linter) globally
2.  Run `graphql-schema-linter schema.graphql`

## Output

```bash
/git/graphql-schema-linter-duplicated-errors/schema.graphql
1:1 The object type `Challenge` is missing a description.        types-have-descriptions
1:1 A `PageInfo` object type is required as per the Relay spec.  relay-page-info-spec
1:1 The object type `Challenge` is missing a description.        types-have-descriptions
2:3 The field `Challenge.id` is missing a description.           fields-have-descriptions
2:3 The field `Challenge.id` is missing a description.           fields-have-descriptions
3:3 The field `Challenge.name` is missing a description.         fields-have-descriptions
3:3 The field `Challenge.name` is missing a description.         fields-have-descriptions
6:1 The object type `Query` is missing a description.            types-have-descriptions
6:1 The object type `Query` is missing a description.            types-have-descriptions
7:3 The field `Query.challenges` is missing a description.       fields-have-descriptions
7:3 The field `Query.challenges` is missing a description.       fields-have-descriptions

✖ 11 errors detected
```
