# Mobile-terminal-layout

移动端布局

设置根元素html的字体大小

var html=document.documentElement;

var width=html.getBoundingClientRect().width;
				
html.style.fontSize=width/18+'px';

