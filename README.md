# TallerLinux

Estructura de carpeta:

/home/ansible/git_workspace/TallerLinux/
                               |
                               |
                               ------LICENSE
                               |
                               ------README.md
                               |
                               ------material/
                               |         |
                               |         --------apache_debian/000-default.conf
                               |         |
                               |         --------apache_redhat/vhost80.conf
                               |         |
                               |         --------base/app.properties
                               |         |        |
                               |         |        ----tablas.sql
                               |         |
                               |         --------tomcat_debian/tomcat.service
                               |         |
                               |         --------tomcat_redhat/tomcat.service
                               |                  |
                               |                  ------------todo.war
                               |
                               -------playbooks/main.yml
                                         |
                                         ------actualizador.yml
                                         |
                                         ------tomcat.yml
                                         |
                                         ------apache.yml
                                         |
                                         ------mysql.yml

Para más información, por favor ver el PDF con nombre: "TallerLinux.pdf"