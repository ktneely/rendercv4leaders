## <<entry.company>>, <<entry.position>>

((* if entry.date_string *))- <<entry.date_string>>
((* endif *))
((* if entry.location *))- <<entry.location>>
((* endif *))
((* for item in entry.highlights *))
- <<item>>
((* endfor *))
((* if entry.responsibilities *))
*Responsibilities*
((* for item in entry.responsibilities *))
- <<item>>
((* endfor *))
((* endif *))
((* if entry.accomplishments *))
*Accomplishments*
((* for item in entry.accomplishments *))
- <<item>>
((* endfor *))
((* endif *))
