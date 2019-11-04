# UserMan2 with Community (UserMan3) 
a branch from UserMan2 master 

### master���� ����� ��Ű�� & Ŭ����  

- controller.RequestMapping (request mapping ���� ���� �� �߰�)
- controller.comm.* (�߰�: Ŀ�´�Ƽ ��� ���� ��Ʈ�ѷ���)
- controller.user.RegisterUserController (Ŀ�´�Ƽ id ó�� �߰�)
- controller.user.UpdateUserFormController (����: UpdateUserController�� ���յ�)
- controller.user.UpdateUserController (UpdateUserFormController ��� ����)

- model.User (Ŀ�´�Ƽ id �ʵ� �߰�)
- model.Community (�߰�)
- model.dao.UserDao (Ŀ�´�Ƽ �Ҽ� ����� �˻� �޼ҵ�� �߰�)
- model.dao.CommunityDao (�߰�)
- model.dao.ConnectionManager (DB ���� ���� �ܺ�ȭ: context.properties ���� �̿�)
- model.dao.JDBCUtil (Sequence�� �̿��� PK �� ���� �� ������ �� Ȯ���� ���� �޼ҵ� �߰�)
- model.service.UserManager (Ŀ�´�Ƽ ���� ��� �߰�)

- resources/context.properties (�߰�: DB ���� ���� �� ����)
- resources/schema.sql (Ŀ�´�Ƽ ���� DB ���̺� & ���ڵ� ���� �߰�)

- WebContent/community/*.jsp (�߰�: Ŀ�´�Ƽ ���� view pages)
- WebContent/css/community.css (�߰�: Ŀ�´�Ƽ ���� style ����)
- WebContent/user/list.jsp (list2.jsp�� ����: JSTL + EL Ȱ�� ����)
- WebContent/user/registerForm.jsp (Ŀ�´�Ƽ �̸� ���� �޴� �߰�: �޴� �׸� �˻� �� ��� �̱���)
- WebContent/user/updateForm.jsp (Ŀ�´�Ƽ �̸� ���� �޴� �߰�)
- WebContent/user/view.jsp (Ŀ�´�Ƽ �̸� �� ��ũ  �߰�)
