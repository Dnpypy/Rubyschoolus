
this folder github rubyschool-us:
git clone https://github.com/rubyschool-us/sinatra-bootstrap-clean.git

this folder cleaned github bootstrap-ruby: 
Cleaned version of https://github.com/bootstrap-ruby/sinatra-bootstrap

���� 22

    ���������-�������:
        �������� post-���������� ��� /visit
        �������� ��� ��������� ������ � ./public/users.txt
        �������� �������� /contacts �� ���������� ������:
            email
            ��������� (���������� html-������� textarea)

            ��� ����������� �������� ������ ����������� � ./public/contacts.txt.

    ���������-��������:
        �� �������� /visit ������������ ������ ����� ����������� ������� ����������� �� ������:
            Walter White
            Jessie Pinkman
            Gus Fring

            ���������� ������������ html-������� (���), ������� ���������� select.

        ��������� ������ ��������� ��������� ������ � ��� �� ����.

    �������� ������� �����-��������: ������� ��, ��� ���� ������ �� 21 ���� (���� �� ������ � �� ������ � ������� sinatra-bootstrap) - ��� ���, ��� �� ������.
   
��� ������� ����� 22 �����:

1. ����� ��� ���� �����(�����,������,email � �.�.) ���� �� ����� 25% � ������, ����� � /visit, /contacts, /admin.
2. ����� ��� �����(form) ���� �� ������ � /visit, /contacts, /admin.
3. ����� � ������ ���� ������ ����� � /visit - �������, /contacts - ������, /admin - �������.
4. �������� ������� �� ������ ������, ���� �������� ������ ������ �� �����-�� �������. 
5. ������� admin.erb � ������, ������� ���������� get/post admin.erb, ������� �� ������� �� admin->admin_panel. 
6. ������� ���� admin_panel.erb � ������� ���������� get ��������.
7. � admin_panel.erb ������� ����� ����� ���� each ���� ������ � ������� bootstrap.
 