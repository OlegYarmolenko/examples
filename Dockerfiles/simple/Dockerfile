FROM mcr.microsoft.com/dotnet/core/sdk:3.1-alpine

RUN yum install epel-release -y \
  python39 \
  python39-pip
RUN pip3 install pyyaml \
  requests \
  snowflake \
  snowflake-connector-python \
  msal \
  msal_extensions \
  pandas \
  azure-keyvault-secrets \
  azure-keyvault-keys \
  azure-identity
