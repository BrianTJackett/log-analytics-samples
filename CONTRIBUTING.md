# Contributing to Log Analytics Samples

Guidelines
- Define any configurable start / end dates with a `let` statement at start of query
- Variables named *Match will be matched with a `contains` operator in the query.  Can be replaced with `==` operator for exact match and improvement in performance.
- Variables named *Filter must remain as a `contains` operator in the query.
- All query files end in ".kql"
- Feel free to suggest additional guidelines for queries and syntax.