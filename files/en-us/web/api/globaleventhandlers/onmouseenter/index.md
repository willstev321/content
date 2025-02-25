---
title: GlobalEventHandlers.onmouseenter
slug: Web/API/GlobalEventHandlers/onmouseenter
page-type: web-api-instance-property
tags:
  - API
  - Event Handler
  - GlobalEventHandlers
  - Property
  - Reference
browser-compat: api.GlobalEventHandlers.onmouseenter
---
{{ ApiRef("HTML DOM") }}

The **`onmouseenter`** property of the
{{domxref("GlobalEventHandlers")}} mixin is the [event handler](/en-US/docs/Web/Events/Event_handlers) for
processing {{domxref("Element/mouseenter_event", "mouseenter")}} events.

The `mouseenter` event is fired when a pointing device (usually a mouse) is
moved over the element that has the listener attached.

## Syntax

```js
element.onmouseenter = handlerFunction;
var handlerFunction = element.onmouseenter;
```

`handlerFunction` is either `null` or a [JavaScript function](/en-US/docs/Web/JavaScript/Reference/Functions)
specifying the handler for the event.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{domxref("Element/mouseenter_event", "mouseenter")}}
- [DOM event handlers](/en-US/docs/Web/Events/Event_handlers)
