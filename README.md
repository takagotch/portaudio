### portaudio
---
https://github.com/gordonklaus/portaudio

```c
// pa.c
#include "_cgo_export.h"

int cb(const void *inputBuffer, void *outputBuffer, unsigned long frames, const PaStremCallbackTimeInfo *timeInfo, PaStreamCallbackFlags statusFlags, void *userData) {
  streamCallback((void*)inputBuffer, outputBuffer, frames, (PaStreamCallbackTimeInfo*)timeInfo, statusFlags, userData);
  return paCountinue;
}

PaStreamCallback* paStreamCallback = cb;
```

```
```

```
```


