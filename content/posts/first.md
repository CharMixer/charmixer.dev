---
title: "First"
date: 2020-11-14T20:32:41Z
draft: false
---

# Testing out hugo

## Some code

```
func FailAllRequestsWithErrorResponse(requests []*Request, status int, code ...int) {
	for _, r := range requests {
		r.Output = NewErrorResponse(r.Index, status, code...)
	}
}
```

## Inline
`NewOkResponse(index int, data interface{}) *client.Response`

## Quote
> What I cannot create, I do not understand
> - Richard Feynman
