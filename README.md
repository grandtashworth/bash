```javascript
 _               _     
| |__   __ _ ___| |__  
| '_ \ / _` / __| '_ \ 
| |_) | (_| \__ \ | | |
|_.__/ \__,_|___/_| |_|
                       
```

Bash Scripts
------------

I always try to stick to some sort of convention which makes the readability of my scripts
quite easy to maintain.


Old Style (pre: 2020)
---------------------
I used this style in most of my career, so historically there are many scripts in the wild
that have the following standards:

Functions: Camel Case - eg: theFunction
Derived Variables: Upper Camel Case - eg: TheDate
Hard Variables: Upper Case - eg: RUNLIST or MESSAGE

New Style (post: 2020)
----------------------
Having spend a little more time at home, and trawling other peoples scripts and code, I came
up with a new style that I think works quite nicely, and makes my scripts very readable

Functions: Start with double underscore and no capitals - eg: __thefunction(){}
Variables: Start with a single underscore and no capitals - eg: _variable

I still have a capitals habit, but that is going to take some liquid amber therapy to get over :-p


