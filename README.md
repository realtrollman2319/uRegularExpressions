# uRegularExpressions [![](https://img.shields.io/github/downloads/realtrollman2319/uRegularExpressions/total.svg)](https://github.com/realtrollman2319/uRegularExpressions/releases)
Regular Expression for uScript2,

self explanatory lmfao

# Note
You will need to add an extra backslash ( \ ) in order for your Regular Expression pattern to work.
https://www.digitalocean.com/community/tutorials/regular-expression-in-java-regex-example#regular-expression-in-java-capturing-groups

# Sample code:
Discord tag:
```
discordTag = "Sous-Chef Roman#4256";
pattern = "^.{3,32}#[0-9]{4}$";
print(RegEx.isMatch(discordTag, pattern) ? "This is a tag." : "This is not a valid tag.");
```
Email:
```
// "[\w._%+-]+@[\w.-]+\.[a-zA-Z]{2,4}" will not work, because it only has single backslashes.

email = "example@example.com";
emailRegex = "[\\w._%+-]+@[\\w.-]+\\.[a-zA-Z]{2,4}";
print(RegEx.isMatch(email, emailRegex) ? "This is an email." : "This is not a valid email.");
```

# THE DOCS:
```
RegEx [Class]:
    +escape(string str)                                                   [get]      : string
    +isMatch(string input, string pattern)                                [get]      : boolean
    +replace(string input, string pattern, string replacement)            [get]      : string
    +split(string input, string pattern)                                  [get]      : array<string>
    +matches(string input, string pattern)                                [get]      : array<string>
```
