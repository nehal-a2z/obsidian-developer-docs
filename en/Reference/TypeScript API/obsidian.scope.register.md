<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [obsidian](./obsidian.md) &gt; [Scope](./obsidian.scope.md) &gt; [register](./obsidian.scope.register.md)

## Scope.register() method

**Signature:**

```typescript
register(modifiers: Modifier[], key: string | null, func: KeymapEventListener): KeymapEventHandler;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  modifiers | [Modifier](./obsidian.modifier.md)<!-- -->\[\] | <code>Mod</code>, <code>Ctrl</code>, <code>Meta</code>, <code>Shift</code>, or <code>Alt</code>. <code>Mod</code> translates to <code>Meta</code> on macOS and <code>Ctrl</code> otherwise. |
|  key | string \| null | Keycode from https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent/key/Key\_Values |
|  func | [KeymapEventListener](./obsidian.keymapeventlistener.md) | the callback |

**Returns:**

[KeymapEventHandler](./obsidian.keymapeventhandler.md)
