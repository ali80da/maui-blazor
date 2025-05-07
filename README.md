# maui-blazor
Fixing Blazor's Current Problems And Introducing Features in Different Versions

برای شروع باید ورژن دات نت استفاده شده در برنامه با دات نت جاری سیستم یکی باشه
### [Switch between dotnet core SDK versions](https://stackoverflow.com/questions/42077229/switch-between-dotnet-core-sdk-versions)

#### You can do this with a global.json file in the root of your project:
```bash
dotnet --list-sdks
```

#### The result will look something like this:
```bash
{
  "sdk": {
    "version": "8.0.100-preview3-010431"
  }
}
```

### []()
#### Open cmd in the root directory of the project and execute the command:
```bash
dotnet new globaljson --sdk-version "sdk version number" --force
```
#### The result will look something like this:
```bash
8.0.408
```




etc
