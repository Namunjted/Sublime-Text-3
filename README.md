
![Alt text](https://octodex.github.com/images/dojocat.jpg  "The Dojocat")
![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")
## __[Sublime Text 3](https://nodeca.github.io/pica/demo/)__ 

----

## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

### Gõ tiếng việt trong sublime text 3

Gõ tiếng việt trên sublime text 3 phiên bản linux Hiện tại đang là phiên bản thử nghiệm. Nếu phát hiện lỗi trong quá trình sử dụng, vui lòng report trên github

Installing :

Vào Preferences->Browse Packages.. Trở lại thư mục sublime-text-3. Vào thư mục Installed Packages. Copy file VN IME.sublime-package vào thư mục Installed Packages.

Usage :

Nhấn phím F2 để bật gõ tiếng việt, nhấn lại phím F2 để tắt. Khi thanh status hiện chữ VN IME : ON là đang bật, VN IME : OFF là đã 
tắt.

### Build system to Python 3

1. __Go to Sublime Text to: Tools -> Build System -> New Build System 
and put the next lines:__

```
{
    "cmd": ["python3", "-i", "-u", "$file"],
    "file_regex": "^[ ]File \"(...?)\", line ([0-9]*)",
    "selector": "source.python"
}

```

Then save it with a meaningful name like: python3.sublime-build

2. Go to Tools -> Build system -> and check python3 

test it with:

import sys
print(sys.version)

Press: Ctrl + b
