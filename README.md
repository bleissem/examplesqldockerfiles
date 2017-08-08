# Example SQL Server Dockerfiles

Example dockerfiles to attach a simple database to a SQL Server image in windows or linux container on Windows 10

# Usage Example - files copied to in C:\Docker\Builds

docker build -t testimage -f C:\Docker\Builds\DockerFileLinux C:\docker\builds\

docker build -t testimage -f C:\Docker\Builds\DockerFileWindows C:\docker\builds\

# Source Images

microsoft/mssql-server-linux

microsoft/mssql-server-windows
