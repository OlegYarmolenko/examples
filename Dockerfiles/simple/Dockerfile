FROM centos

RUN yum install epel-release -y
RUN yum install python39 -y
RUN yum install python39-pip
RUN pip3 install pyyaml
RUN pip3 install requests snowflake snowflake-connector-python msal msal_extensions pandas azure-keyvault-secrets azure-keyvault-keys azure-identity
RUN echo "I'm working!"
