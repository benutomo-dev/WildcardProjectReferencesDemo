# WildcardProjectReferencesDemo

In VS17.10.3 (perhaps when a project exists in a nested folder), the referenced project specified in the following writing does not appear in the Solution Explorer.

```xml
<ProjectReference Include="..\ClassLibrary*\*.csproj" />
```

![image](https://github.com/benutomo-dev/WildcardProjectReferencesDemo/assets/52617232/39e80113-6415-4e69-b4d1-1e30bd27d191)

Until VS17.9, the same writing style was displayed as follows.

![image](https://github.com/benutomo-dev/WildcardProjectReferencesDemo/assets/52617232/d74f5f04-2907-4ec9-8533-73ea9458dfce)
