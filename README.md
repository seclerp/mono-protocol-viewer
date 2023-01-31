# Chrome DevTools Protocol Extensions for Mono WASM Proxy

.NET uses a special CDP-based debug proxy that handles messages from three different actors: a CDP-based debugger frontend, WASM Mono runtime, and the browser.  

This viewer allows discovering additional non-documented pieces that are provided by debug proxy for debugger frontend for handling Mono or .NET-specific features.

> **Warning**: **There are no official specifications** of such a protocol extension. It could be changed frequently and without notice, so please use carefully. 

Useful links:
* [`mono_wasm_protocol.json`](specs/mono_wasm_protocol.json): unofficial protocol extension JSON specification
* [Mono WASM Proxy Sources](https://github.com/dotnet/runtime/tree/main/src/mono/wasm/debugger)

Based on the excellent [Minimalistic DevTools Protocol Viewer](https://vanilla.aslushnikov.com/) by [aslushnikov](https://github.com/aslushnikov).