# sprint_challenge1

go to parent directory and then
on windows set FLASK_APP=aq_dashboard2.py
on linux or max FLASK_APP=aq_dashboard2.py

url/refresh will refresh and add to the database.

Record.query.filter(Record.value >= 10).all()
produces this error
<bound method Query.all of <flask_sqlalchemy.BaseQuery object at 0x0000016B76055408>>
*** TypeError: __repr__ returned non-string (type method)
