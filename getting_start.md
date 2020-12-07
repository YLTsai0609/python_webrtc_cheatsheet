# Github

[WebRTC and ORTC implementation for Python using asyncio](https://github.com/aiortc/aiortc)

RTSP with browser support

# Why this?

Flask事實上不支援RTSP(Real Time Streamming Protocol)，RTS被WebRTC包起來，python透過asun實作了WebRTC以及ORTC，可作為Video Streamming的標準工具，在Python中我們已經建立起電腦視覺的演算法及Pipeline，接著就直接透過WebRTC作為API接口吧!

# installation

 `pip install aiortc`

# Getting Start

把github上的example，clone下來玩，目前發現

1. webcam.py只支援1對1，1個server對多個client需要手刻一些東西，像是把Track複製給很多client
