# profile.<br>
profile详解<br>
~/.profile 表示当前用户生效<br>
/etc/profile 表示所有用户生效<br>
.bash_profile 打开某文件夹后生效，如果在根目录，打开cmd会默认打开根目录加载，如果是其他目录下则打开该目录后才生效
必须要PATH才能够生效！ xxx_PATH只是主路径， source profile后才有效<br>
export SCALA_HOME=/Users/23mofang/Desktop/hail/scala-2.12.6<br>
#export SCALA_HOME=$PATH:/Users/23mofang/Desktop/hail/scala-2.12.6<br>
export PATH=$PATH:$SCALA_HOME/bin<br>
注意第一个为绝对路径=/Users/23mofang/Desktop/hail/scala-2.12.6<br>
第二个前面一定要将$PATH 这是一个系统路径会把所有环境变量串在一起，不过没有$PATH 就会全部只向该变量
