# harmo.lv2
Additive synthesizer<br/>
https://github.com/sjaehn/lv2tutorial/tree/master/mySimpleSynth<br/>
```
g++ -fvisibility=hidden -fPIC -Wl,-Bstatic -Wl,-Bdynamic -Wl,--as-needed -shared -pthread `pkg-config --cflags lv2` -lm `pkg-config --libs lv2` mySimpleSynth.cpp -o mySimpleSynth.so
