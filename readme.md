JSON data of US Government Shutdowns

Source: http://en.wikipedia.org/wiki/Government_shutdown_in_the_US

# Example

Python example:

    >>> import json
    >>> data = file('shutdowns.json').read()
    >>> shutdown_data = json.loads(data)
    >>> shutdown_data
    [{u'end': u'1976-10-11', u'senate': u'Democrat', u'house': u'Democrat', u'days': 10, u'start': u'1976-09-30', u'president': u'Ford'}, {u'end': u'1977-10-13', u'senate': u'Democrat', u'house': u'Democrat', u'days': 12, u'start': u'1977-09-30', u'president': u'Carter'}, {u'end': u'1977-11-09', u'senate': u'Democrat', u'house': u'Democrat', u'days': 8, u'start': u'1977-10-31', u'president': u'Carter'}, {u'end': u'1977-12-09', u'senate': u'Democrat', u'house': u'Democrat', u'days': 8, u'start': u'1977-11-31', u'president': u'Carter'}, {u'end': u'1978-10-18', u'senate': u'Democrat', u'house': u'Democrat', u'days': 18, u'start': u'1978-09-30', u'president': u'Carter'}, {u'end': u'1979-10-12', u'senate': u'Democrat', u'house': u'Democrat', u'days': 12, u'start': u'1979-09-30', u'president': u'Carter'}, {u'end': u'1981-11-23', u'senate': u'Republican', u'house': u'Democrat', u'days': 2, u'start': u'1981-11-20', u'president': u'Reagan'}, {u'end': u'1983-10-02', u'senate': u'Republican', u'house': u'Democrat', u'days': 1, u'start': u'1982-09-30', u'president': u'Reagan'}, {u'end': u'1982-12-21', u'senate': u'Republican', u'house': u'Democrat', u'days': 3, u'start': u'1982-12-17', u'president': u'Reagan'}, {u'end': u'1983-11-14', u'senate': u'Republican', u'house': u'Democrat', u'days': 3, u'start': u'1983-11-10', u'president': u'Reagan'}, {u'end': u'1984-10-03', u'senate': u'Republican', u'house': u'Democrat', u'days': 2, u'start': u'1984-09-30', u'president': u'Reagan'}, {u'end': u'1984-10-05', u'senate': u'Republican', u'house': u'Democrat', u'days': 1, u'start': u'1984-10-03', u'president': u'Reagan'}, {u'end': u'1986-10-18', u'senate': u'Republican', u'house': u'Democrat', u'days': 1, u'start': u'1986-10-16', u'president': u'Reagan'}, {u'end': u'1987-12-20', u'senate': u'Democrat', u'house': u'Democrat', u'days': 1, u'start': u'1987-12-18', u'president': u'Reagan'}, {u'end': u'1990-10-09', u'senate': u'Republican', u'house': u'Democrat', u'days': 4, u'start': u'1990-10-05', u'president': u'HW Bush'}, {u'end': u'1995-11-19', u'senate': u'Republican', u'house': u'Republican', u'days': 5, u'start': u'1995-11-13', u'president': u'Clinton'}, {u'end': u'1996-01-06', u'senate': u'Republican', u'house': u'Republican', u'days': 21, u'start': u'1995-12-15', u'president': u'Clinton'}, {u'end': None, u'senate': u'Democrat', u'house': u'Republican', u'days': None, u'start': u'2013-09-30', u'president': u'Obama'}]
    >>> len(shutdown_data)
    18
