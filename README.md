# DESKTOP-ICONS
Arrow remove from desktop icons windows

## 🚀 Steps to follow 

~ press
`windows` + `R`

~ type
```bash
regedit
```

~ view
`HKEY_LOCAL_MACHINE`

~ go to
`SOFTWARE`

~ go to
`Microsoft`

~ go to
`Windows`

~ go to
`CurrentVersion`

~ go to
`Explorer` -> `right click` -> `new` -> `Key` 

~ name it
```bash
Shell Icons
```

~ in shell icons
`right click` -> `new` -> `String Value`

~ add value
```bash
29
```

~ double click to value

~ add data
```bash
%windir%\System32\shell32.dll,-50
```

~ open Task Manager

~ go to `File Explorer` ->`right click` -> `restart`













