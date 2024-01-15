## SUBQUERY
```
A subquery is a query within another query, also called as nested or inner query.
It can be used with select,insert,update and delete statements.
It can be used in where clause,from clause and joins.
subquery must be enclosed in parentheses.
The subquery generally executes first. If it has no co-relation with the main query, so the result of a outer query is dependent on subquery.

Co-related subquery
The subquery that uses the values from outer query or dependent on the outer query is called co-related subquery.
In co-corelated subquery, the result of outer query is dependent on inner query and the result of inner query is dependent on outer query.
```
## IN, EXISTS
```
IN : To match a column or expression against list of values, the values can be direct or from result of a subquery.
Syntax:
select */clolumn_list from table where col in (values....);
select */clolumn_list from table where col in (subquery);

EXISTS: Returns True or False  based on subquery result that has condition to evaluate.
syntax: 
select */column_list from table where exists(select * from table where condition);
Note: Not in is opposite of IN and NOT EXISTS the opposite of EXISTS.
```


