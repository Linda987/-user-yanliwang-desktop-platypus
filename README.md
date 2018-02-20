# MyRepository


def find_char(s,t):
    return map(lambda str: str.find(t),s.split())

s = 'today is a nice day'

print find_char(s,'i')
