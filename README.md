# Connections

This is a tiny package (more of a small set of custom commands) that draws connections between words written in a single line. It’s built on TiKZ, and works by defining each thing you want to connect with lines as a node (which I’ve called a `target` in the package).

```latex
\ex. [\subsc{CP} [\subsc{TP} T [\subsc{VoiceP} \target{Voice}
[\subsc{\textit{v}P} \target[v]{\textit{v}} [\subsc{KP} \target{K}
[\subsc{DP} \target{D} [\subsc{\textit{n}P} \textit{n} ]]]]]]]
\connect{v}{K}
\connect[over,densely dashed]{Voice}{D}
```

!(https://github.com/rcraioveanu/connections/blob/master/connections-output.png)
