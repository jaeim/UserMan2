# UserMan2 with Community using Ajax (UserMan3a) 
a branch from UserMan2 master 
adding community functionalities and using Ajax calls to JSON controllers

- /community/list
- /user/register/form 

### with_Community_(UserMan3) branch ���� ����� Ŭ����  

- controller.RequestMapping (request mapping ���� ���� �� �߰�)
- controller.comm.ListCommunityController (ListAndViewCommunityController�� ��ü: listAndView.jsp �� ����)
- controller.comm.ListCommunityJsonController (�߰�: Ŀ�´�Ƽ ����Ʈ �˻� �� JSON �������� ���)
- controller.comm.ViewCommunityJsonController (�߰�: Ư�� Ŀ�´�Ƽ ���� �˻� �� JSON �������� ���) 

- WebContent/user/registerForm.jsp (ListCommunityJsonController�� ���� Ajax ȣ�� �߰�)
- WebContent/community/list.jsp (listAndView.jsp�� ��ü: ViewCommunityJsonController�� ���� Ajax ȣ��)

