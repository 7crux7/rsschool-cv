# Yaroslav Kluchnikov

## contacts
* Location: Homel, Belarus
* Phone: +375 44 5842255
* Email: Kluchnikov03@gmail.com
* GitHub: 7crux7

## About me
I am studying programming in college on the 1st year of "programmer", I want to enter the IT as soon as possible, everything is very interesting there.

## Skills
* Python
* HTML
* CSS
* Java Script
* Git & GitHub

## Code exemple
```
def generate_hashtag(s):
    
            if len(s) > 140 or len(s) < 1:
                return False
            
            s = s.split()
            for index in range( len(s) ):
                if s[index].isalpha():
                    if len(s[index]) > 1:
                        s[index] = s[index][0].upper() + s[index][1:].lower()
                    else:
                        s[index] = s[index][0].upper()
                    
            return '#' + ''.join(s)
```

## Education
* Python video course
* University: Homel Trade and Economics Kollege (present)
* Rolling scopes school stage 0 (present)

## Language:

English - A2 level 

Russian - native speaker