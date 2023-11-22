# Demonstrate issue with RDG when handling Query parameters with default values

RDG does not like the presence of `[FromQuery]` on an optional parameter in the request delegate.
Simply removing the attribute fixes the issue.
