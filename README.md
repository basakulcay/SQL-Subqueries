# Subqueries

A non-correlated subquery is a subquery that can be run independently of the outer query and as we saw, can be used to complete a multi-step transformation. 

In a correlated subquery, the subquery can not be run independently of the outer query. The order of operations is important in a correlated subquery:

    A row is processed in the outer query.
    Then, for that particular row in the outer query, the subquery is executed.
