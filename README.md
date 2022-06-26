# Event Maker Documentation

:warning: | To use this you need to know how to use plugins!
:---: | :---

# Creating an Event
![](https://raw.githubusercontent.com/Haynster/Event-Maker-Plug-In-Documentation/main/70FB8F11-6927-4D05-8DF9-9BE5D7254CD4.png)

- First you need to create an array with 2 values
- In value 0, Type in the title of the event
- In value 1, Is where you put the event code (you dont need to type them here you can code in and ide

# Coding the events
> **Each event needs to have a ";" after it if you are using something where you can have multiple lines
> If you are using a program with only one line, then you will need to add a "; " after it**

*If you are using a program with multiple lines*
```
event.action(values);
event.action(values);
event.action(values);
```
*If you are using a program with on line*
```
event.action(values); event.action(values); event.action(values);
```

## The Console Log
**This plugin features a console log**

### To use it you can broadcast
---
> *To Log a string*
> Broadcast: Log
> Value: Whatever String

> *To Clear the Log*
> Broadcast: Clear Log

> *To Display the Log*
> Broadcast: Display Log

### You can also do this with event code
---
> *To Log a string*
> `console.log(string)`

> *To Display the Log*
> `console.display()`

> *To Clear the Log*
> `console.clear()`
