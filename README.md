# o2-cylinder-tracker

Simple form aid quick check in/check out of oxygen cylinders. QR codes will be put oxygen cylinder. Those QR codes will be scanned on refill depos and/or hospitals. This will create a stream of data - which cylinder was where at what time. This data stream can be used later to answer questions like which cylinder is out of circulation, what is the churn rate of cylinders etc.

Uses [Web Media Capture API](https://developer.mozilla.org/en-US/docs/Web/API/Media_Streams_API) to access device camera and [jsQR](https://github.com/cozmo/jsQR) to scan. [Geo location API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API) for location

Web media capture and Geo location requires site to be served over `https` to work.


[Try it](https://alliance4nep.github.io/o2-cylinder-tracker/)

![https://alliance4nep.github.io/o2-cylinder-tracker/](data:image/gif;base64,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)

