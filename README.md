## 准备

到 <https://www.nasm.us/> 下载 nasm.exe，放进 C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\VC 目录下面
## 编译

右键，生成解决方案，就这么简单

## 更新代码

如果想从各个项目的源仓库更新代码，直接把代码下载后塞进 src\thirdparty 各项目对应文件夹即可。
git clone https://github.com/passerbya/libass-msvc.git
git submodule update --init --recursive --remote

```
以下是源仓库地址和对应的文件夹：

[submodule "src/thirdparty/libass/libass"]
	path = src/thirdparty/libass/libass
	url = https://github.com/passerbya/libass.git
[submodule "src/thirdparty/fontconfig/fontconfig"]
	path = src/thirdparty/fontconfig/fontconfig
	url = https://github.com/ShiftMediaProject/fontconfig.git
[submodule "src/thirdparty/fribidi/fribidi"]
	path = src/thirdparty/fribidi/fribidi
	url = https://github.com/ShiftMediaProject/fribidi.git
[submodule "src/thirdparty/harfbuzz/harfbuzz"]
	path = src/thirdparty/harfbuzz/harfbuzz
	url = https://github.com/ShiftMediaProject/harfbuzz.git
[submodule "src/thirdparty/liblzma/liblzma"]
	path = src/thirdparty/liblzma/liblzma
	url = https://github.com/ShiftMediaProject/liblzma.git
[submodule "src/thirdparty/libxml2/libxml2"]
	path = src/thirdparty/libxml2/libxml2
	url = https://github.com/ShiftMediaProject/libxml2.git
[submodule "src/thirdparty/freetype2/freetype2"]
	path = src/thirdparty/freetype2/freetype2
	url = https://gitlab.freedesktop.org/freetype/freetype.git
[submodule "src/thirdparty/libiconv/libiconv-for-Windows"]
	path = src/thirdparty/libiconv/libiconv-for-Windows
	url = https://github.com/pffang/libiconv-for-Windows.git
```