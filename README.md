FluxJpeg.Core
=============

Clone of fjcore library that seems to be stagant on google code
https://code.google.com/p/fjcore

NuGet Package: https://nuget.org/packages/Flux.Jpeg.Core/

**Some Changes:**

* **Breaking Change** Changed Resize to use specific x,y dimensions and moved old resize to ResizeToScale
* Also wired up the ProgressChanged event to actually fire
