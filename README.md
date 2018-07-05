# profile
profile详解
~/.profile 表示当前用户生效
/etc/profile 表示所有用户生效
.bash_profile 打开某文件夹后生效，如果在根目录，打开cmd会默认打开根目录加载，如果是其他目录下则打开该目录后才生效
必须要PATH才能够生效！ xxx_PATH只是主路径， source profile后才有效
