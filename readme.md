# Resume

This is my resume written in groff.

# Requirements

- groff (1.22.4 required)
- GNU make

# Compilation

```
make
```

# Examples

[Programming Resume](./programming_resume.pdf)

[Coaching Resume](./coaching_resume.pdf)

To generate programming_resume.ms from programming_resume.template

'''
ctemplate programming_cover.template company "Bitwarden" position "Software Engineer"
'''

[ctemplate](https://github.com/Spacefreak18/ctemplate)
