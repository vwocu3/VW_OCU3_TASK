FROM mcr.microsoft.com/windows/nanoserver:1803-amd64
RUN net user John B@dP@ssw0rd /ADD
COPY . /
RUN msiexec /quiet /i sample.msi ACCOUNT=%COMPUTERNAME%\John PASSWORD=B@dP@ssw0rd