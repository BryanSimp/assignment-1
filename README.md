# This is my Heading

## I think cats are cool but so are dogs

<code>
def add_odd(func):
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

### This is an image of my cat at home

![my cat zuko from home](https://github.com/user-attachments/assets/bf121d4a-ac88-4555-821d-4907e9866825)

