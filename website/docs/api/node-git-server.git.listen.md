---
id: node-git-server.git.listen
hide_title: true
custom_edit_url: null
title: Git.listen() method
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) > [node-git-server](./node-git-server.md) > [Git](./node-git-server.git.md) > [listen](./node-git-server.git.listen.md)

## Git.listen() method

starts a git server on the given port

<b>Signature:</b>

```typescript
listen(port: number, options?: GitServerOptions, callback?: () => void): Git;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  port | number | the port to start the server on |
|  options | GitServerOptions | the options to add extended functionality to the server |
|  callback | () => void | the function to call when server is started or error has occurred |

<b>Returns:</b>

[Git](./node-git-server.git.md)