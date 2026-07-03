get win

int a
bol b
chr c
flt d
dle e
int isrunning=1

mac{
x2,y2
x1=y1
}

chr* window=crtwindow((600,800),"window1","red")

def out1{
out window('.\1.png',(250,250))         //双引号文本，单引号路径
out "窗口已创建"
}

def puls(a,b){
a+=b
rt a
}

def g{
lop isrunning==1{
out1
ent{
if key==ESCAPE
isrunning=2
elif key==A
a=1
el
b=1
}

out window(rect((200,200),(0,0,0)),(200,100))

fil window("red")

clk()
}
}

main _init_{
g
wit(500)
ext()
}
//你只写win版就可以了，不是写单片机的语言奥，就是创建窗口，有存储功能，可以播放音频，处理按键信息一堆的语言。后缀.krt，库文件.krh，支持.dll
