# create project
- dotnet new console -lang="F#" -o="CleanArchitecture"

# ping確認
- dotnet add package Microsoft.AspNetCore
- dotnet add package Microsoft.AspNetCore.App
- dotnet watch
- curl -v http://localhost:5000/ping

# 犬種固定で返す
- curl -v http://localhost:5000/dog