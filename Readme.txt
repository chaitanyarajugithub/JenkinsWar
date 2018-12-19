<tomcat-users>

  <!-- user manager can access only manager section -->
  <role rolename="manager-gui" />
  <user username="manager" password="_SECRET_PASSWORD_" roles="manager-gui" />

  <!-- user admin can access manager and admin section both -->
  <role rolename="admin-gui" />
  <user username="admin" password="_SECRET_PASSWORD_" roles="standard,manager-gui,admin-gui" />

</tomcat-users>
