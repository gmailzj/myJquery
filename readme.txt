touch README.md //�½�˵���ļ�
git init //�ڵ�ǰ��ĿĿ¼�����ɱ���git����,������һ������.gitĿ¼


git config --global user.email "gmailzj@qq.com"
git config --global user.name "gmailzj"


ssh-keygen -t rsa -C "gmailzj@qq.com"
Ȼ����github���key �� id_rsa.pub �е�ȫ�����ݸ���

����
ssh -T git@github.com

git add . //��ӵ�ǰĿ¼�е������ļ�������
git commit -m "first commit" //�ύ������Դ��⣬�������ύע��
git remote add  origin  git@github.com:gmailzj/myJquery.git��ӵ�Զ����Ŀ������Ϊorigin
git push -u origin master //�ѱ���Դ���push��github ����Ϊorigin��Զ����Ŀ�У�ȷ���ύ