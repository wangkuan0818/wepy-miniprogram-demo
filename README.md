# wepy-miniprogram-demo

wepy-miniprogram-demo


npm install -g wepy-cli
wepy init standard my-project
npm  install
wepy build --watch

# WePY��Ŀ��Ŀ¼�ṹ
������ dist                   С�������д���Ŀ¼����Ŀ¼��WePY��buildָ���Զ��������ɣ��벻Ҫֱ���޸ĸ�Ŀ¼�µ��ļ���
������ node_modules           
������ src                    �����д��Ŀ¼����Ŀ¼Ϊʹ��WePY��Ŀ���Ŀ¼��
|   ������ components         WePY���Ŀ¼���������������ҳ�棬��������ҳ�������������ã�
|   |   ������ com_a.wpy      �ɸ��õ�WePY���a
|   |   ������ com_b.wpy      �ɸ��õ�WePY���b
|   ������ pages              WePYҳ��Ŀ¼����������ҳ�棩
|   |   ������ index.wpy      indexҳ�棨��build�󣬻���distĿ¼�µ�pagesĿ¼����index.js��index.json��index.wxml��index.wxss�ļ���
|   |   ������ other.wpy      otherҳ�棨��build�󣬻���distĿ¼�µ�pagesĿ¼����other.js��other.json��other.wxml��other.wxss�ļ���
|   ������ app.wpy            С���������ȫ�����ݡ���ʽ���������ӵȣ���build�󣬻���distĿ¼������app.js��app.json��app.wxss�ļ���
������ package.json           ��Ŀ��package����

es6: ��Ӧ�ر�ES6תES5ѡ��رա� ��Ҫ��δ�رջ����б���

postcss: ��Ӧ�ر��ϴ�����ʱ��ʽ�Զ���ȫѡ��رա� ��Ҫ��ĳЩ�����©������Ҳ�����б���

minified: ��Ӧ�رմ���ѹ���ϴ�ѡ��رա���Ҫ�������󣬻ᵼ�����computed, props.sync �ȵ�����ʧЧ����ע��ѹ�����ܿ�ʹ��WePY�ṩ��buildָ����棬���������ؽ����Լ�Demo��Ŀ��Ŀ¼�е�wepy.config.js��package.json�ļ�����

urlCheck: ��Ӧ����鰲ȫ����ѡ������� ��������úð�ȫ��������رա�