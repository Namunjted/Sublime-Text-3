
## __[Sublime Text 3(https://www.sublimetext.com/)__ 

----
### __Gõ tiếng việt trong sublime text 3__

Gõ tiếng việt trên sublime text 3 phiên bản linux Hiện tại đang là phiên bản thử nghiệm. Nếu phát hiện lỗi trong quá trình sử dụng, vui lòng report trên github

- Installing :

Vào __Preferences->Browse Packages__. Trở lại thư mục sublime-text-3. Vào thư mục __Installed Packages__. Copy file __VN IME.sublime-package__ vào thư mục __Installed Packages__.

- Usage :

Nhấn phím __F2__ để bật gõ tiếng việt, nhấn lại phím F2 để tắt. Khi thanh status hiện chữ VN IME : ON là đang bật, VN IME : OFF là đã 
tắt.

### __Build system to Python 3__

- Go to __Sublime Text__ to: __Tools -> Build System -> New Build System__ and put the next lines:

```
{
    "cmd": ["python3", "-i", "-u", "$file"],
    "file_regex": "^[ ]File \"(...?)\", line ([0-9]*)",
    "selector": "source.python"
}

```

Then save it with a meaningful name like: python3.sublime-build

- Go to __Tools -> Build system -> and check python3__ 

test it with:
```
import sys
print(sys.version)
```
Press: __Ctrl + b__

