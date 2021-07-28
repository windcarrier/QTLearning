# QT程序的发布
1. 使用Release编译程序
2. 打开QT命令行窗口(注意要与使用的编译器相同 如：MinGW-64)
3. 在QT命令窗口中进入Release的exe所在的文件目录（如：C:\Users\CWang\Downloads\Desktop_Qt_5_14_2_MinGW_64_bit-Release）
4. 使用windeployqt + exe名称，将程序说依赖的QT的dll拷贝到对应文件目录中
5. 程序用到的icon等资源需要自己进行拷贝，目前拷贝位置是Release上级目录。后续有其他方法希望在这里进一步更新。
