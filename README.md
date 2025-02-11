#This is my Heading

##I think cats are cool but so are dogs

<code>def add_odd(func):
    def wrapper(*args, **kwargs):
        result = func(*args, **kwargs)
        if isinstance(result, (int, float)) and result % 2 != 0:
            return result + 1
        return result
    return wrapper

@add_odd
def return_number(num):
    return num

print(return_number(5))
print(return_number(4))
</code>

###This is an image of my cat at home

![Zuko My Cat](https://photos.fife.usercontent.google.com/pw/AP1GczMbXJBt2yEDSvPGng0okTz3Ew4EtZ6bZt8Frbe5kMgTQLfpJAJv0yH-4g=w783-h919-s-no-gm?authuser=0)
