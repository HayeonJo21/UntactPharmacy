# UserMan3 using Bootstrap and MyBatis (UserMan3c) 
a branch from UserMan2 master 
- adding community functionalities  
- using Bootstrap
- implementing Community DAO using MyBatis data mapper 
 
### userman3b�κ��� ����/�߰��� ���ϵ�

- model.{Community, User}: implements Serializable interface
- model.dao.CommunityDAO
- model.dao.{CommunityMapper.java, CommunityMapper.xml}: Mapper interface, Mapper XML
- model.service.UserManager#findCommunity()
- resources/mybatis-config.xml (MyBatis ���� ����)
- pom.xml: MyBatis dependency ���� �߰�