## Portable - win32

```
nativefier --name "YMoviePortable" "https://ymovie.streamcinema.cz/" --internal-urls ".*" "NATIVEFIER" --tray true --single-instance true --portable true --file-download-options true --icon "C:\Users\x\Pictures\Saved Pictures\logo-512x512.ico" --background-color #000000
```



## Not portable - win32

```
nativefier --name "YMovie" "https://ymovie.streamcinema.cz/" --internal-urls ".*" "NATIVEFIER" --tray true --single-instance true --portable false --file-download-options true --icon "C:\Users\x\Pictures\Saved Pictures\logo-512x512.ico" --background-color #000000
```



## Portable - linux

```
nativefier --name "YMoviePortable" "https://ymovie.streamcinema.cz/" --internal-urls ".*" "NATIVEFIER" --tray true --single-instance true --portable true --file-download-options true --icon "C:\Users\x\Pictures\Saved Pictures\logo-512x512.ico" --background-color #000000 -p linux
```



## Not portable - linux

```
nativefier --name "YMovie" "https://ymovie.streamcinema.cz/" --internal-urls ".*" "NATIVEFIER" --tray true --single-instance true --portable false --file-download-options true --icon "C:\Users\x\Pictures\Saved Pictures\logo-512x512.ico" --background-color #000000 -p linux
```



## Portable - Mac

```
nativefier --name "YMoviePortable" "https://ymovie.streamcinema.cz/" --internal-urls ".*" "NATIVEFIER" --single-instance true --portable true --file-download-options true --icon "C:\Users\x\Pictures\Saved Pictures\logo-512x512.icns" --background-color #000000 -p mac
```



## Not portable - Mac

```
nativefier --name "YMovie" "https://ymovie.streamcinema.cz/" --internal-urls ".*" "NATIVEFIER" --single-instance true --portable false --file-download-options true --icon "C:\Users\x\Pictures\Saved Pictures\logo-512x512.icns" --background-color #000000 -p mac
```
