README:

1. create database name dbwcs using mySql
   dan sesuaikan setting database mysql di appsetting.json
2. dotnet ef migrations add initCreatedb
3. dotnet ef database update
4. dotnet run