# Android-S-Reacton-Enhancer
### EXKonan @ Github

## English
This simple Magisk module was modified from https://github.com/robgiering/keep10dark by editing system.prop, module.prop and install.sh.  
It enhances HWUI, FUSE-Passthrough and SmartDark under Android 12.  
Thanks to @robgiering @topjohnwu for the strong support.  
### Usage:
System Requirement  
Android 12 & Vulkan support  
Magisk patched Kernel  
Flash this module via Magisk Dircetly  

### Optional but highly recommended:
#### Use with F2FS filesystem for the Ultimate Experience:
"In this part,you are required to Download
A up-to-date TWRP or other recovery with F2FS support,use to convert the /data and /cache;
An F2FS-supported kernel in which use to load the F2fs partition correctly.

### Attention:
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

This feature may cause compatibility issues such as splash screen/dead phone/locked logos on systems that are highly modified/not fully debugged (e.g. MIUI), so you can choose to go into Recovery and delete the module's folder and reboot.  

##### module's folder path in Magisk V24.3:
/data/adb/modules/Android-S-Reacton-Enhancer  

### Minimum Requirement
Android 10&11 can be used with other features by editing the module file and commenting out/deleting the FUSE-Passthrough line in the gap before rebooting after flash.  
Android 11 has the option to roll back FUSE to SDcardFS to enhance IO performance, but no method is provided here, so you can turn to a search engine for help.

## 简体中文
这个简单的Magisk模块是从 https://github.com/robgiering/keep10dark 通过编辑system.prop,module.prop和install.sh修改而成的，  
主要增强了Android12下的UI渲染，用户空间文件系统穿透和SmartDark功能。  
感谢@robgiering @topjohnwu 的强力支持。  
### 使用方法:
检查系统要求  
安卓12&Vulkan支持  
Magisk修补过的内核  
直接通过Magisk刷入  

### 可选但强烈推荐的:  
#### 配合F2FS文件系统使用以获得极致体验  
一个最新的TWRP或其他支持F2FS的恢复程序，用来转换/data和/cache;
一个支持F2FS的内核，用来正确加载F2FS分区.

## 免责声明
作者虽然在自己的设备上的
PixelExperience_raphael-12.0-20220222-1331-OFFICIAL
@RedMi K20 Pro
做过测试充分可用且没有碰上任何bug,
但由于各路国内外Android系统提供商的各种魔改
和没有时间&没有精力&没有条件做各种完善的测试，
仅表示该方法在理论上可行，但为避免争议&无故背锅，我在此定义为"不做任何明示或者暗示的担保"，
使用者(您)需要自行承担风险,具体情况具体分析。
在开拓道路/疆土/视野的过程中，风险与机遇总是并存的。

### 善后处理
该模块对高度魔改过后/未进行全面Debug的系统(如MIUI)可能会存在兼容性问题如花屏/死机/卡Logo等问题，  
这时候进Recovery把该模块的文件夹删除，重启即可.  
##### Magisk V24.3的模块路径:
/data/adb/modules/Android-S-Reacton-Enhancer

### 最小系统支持
安卓10&11 可以通过在刷入后重启前的间隙编辑模块文件，注释/删掉FUSE-Passthrough一行来使用其他功能  
Android11可以选择将FUSE回退到SDcardFS以增强IO性能，但此处不提供方法,您可以自行求助搜索引擎

### External Links:
#### Principle of the method
OpenGL vs SkiaGL vs Vulkan:  
https://segmentfault.com/a/1190000017099186

FUSE-Passthrough  
https://source.android.com/devices/storage/fuse-passthrough

SmartDark  
https://forum.xda-developers.com/t/how-to-auto-override-force-dark-mode-in-android-q.4023907/

#### System resources
Magisk  
https://github.com/topjohnwu/Magisk

LineageOS  
https://download.lineageos.org

TWRP Recovery  
https://twrp.me/Devices/

### licenses
http://creativecommons.org/licenses/by-sa/4.0/
本作品采用知识共享署名-相同方式共享 4.0 国际许可协议进行许可。
