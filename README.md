# azure-function-dotnet-playground

### Generate Function
```ssh
func init LocalFunctionProj --dotnet
cd LocalFunctionProj
func new --name HttpExample --template "HTTP trigger" --authlevel "anonymous"
```