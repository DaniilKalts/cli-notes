### apropos

**Usage:** Search the manual pages for names and descriptions. <br />
More information: https://manned.org/apropos. <br />

Search for a keyword using a regular expression:

```
apropos regular_expression
```

Search without restricting the output to the terminal width ([l]ong output):

```
apropos --long regular_expression
```

Search for pages that match all the expressions given:

```
apropos regular_expression_1 --and regular_expression_2 --and regular_expression_3
```
