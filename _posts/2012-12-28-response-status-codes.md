---
title: 'Template'

layout: nil
---

### Success

Successes differ from errors in that their body may not be a simple response object with a code and a message. The headers however are consistent across all calls:

* `GET`, `PUT`, `DELETE` returns `200 OK` on success,
* `POST ` returns 201 on success,

When [retrieving stuff](#get-stuff) for example:

```Status: 200 OK```
```{
    {
        id: thing_1,
        name: 'My first thing'
    },
    {
        id: thing_2,
        name: 'My second thing'
    }
}```
