T("efx.dist")
=============
## ディストーション ##

```timbre
var src = "/timbre.js/misc/audio/guitar.wav";
var audio = T("audio", {isLooped:true}).load(src, function(res) {
    
    T("efx.dist", {preGain:-30, postGain:12}, this).play();

});
```