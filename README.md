����һ��bootstrapt4����ϰ

�õ��Ĺ��ߣ�

bootstrapt��CDN��https://getbootstrap.com/
������������package

*************************************************************************************
1.�����

step1.����Ŀ¼�˽�index.html
��CMD����bootstrapt4Ŀ¼
mkdir bootstrapt4

step2.��index.htmlͷ������cdn
дһ��html5�Ľṹ
link ���� bootstrapt4 ��css��cdn  ��cdn�ο�λ�ã�https://getbootstrap.com/��
���cdn��ǰ��������Ҫ
bootstrap4.css-->jQuery.is-->popper.js-->bootstrap.js

step3.�Զ����css��js
�Զ���Ķ��Ǽ������һ��

step4.���Ŀ�ķ�����
cmd����
yarn init -y

��װbrower-sync
yarn add browser-sync

�ص�package.json�ļ�
����
"scripts":{
    "start":"./node_modules/.bin/browser-sync start --server --no-notify --files='index.html, *.css, *.js'"
  }

�ص�cmd������Ŀ
yarn start

**************************************************************************************
2.�github��Ŀ

step1.�½�.gitignore
�ڱ����½�.gitignore�ļ�����http://github.com/github/gitignore
�ҵ�Node.gitignore�ļ���������Ĵ�����ȫ�����������ص�.gitignore�ļ�


step2.��CMD������Ŀ����githug
cmd ���� $ cd ��Ŀλ��

$ cd 

