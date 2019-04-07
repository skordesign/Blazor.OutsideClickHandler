# SkorBlazor.OutsideClickHandler
Detect click outside of element for Blazor
# Using
#### 1.Install Nuget package or build this project and add reference.
Nuget: [SkorBlazor.OutsideClickHandler](https://www.nuget.org/packages/SkorBlazor.OutsideClickHandler/)
#### 2.Add to `_ViewImports.cshtml`
```csharp
@addTagHelper *, SkorBlazor.OutsideClickHandler
```

#### 3.Use it in `*.cshtml` files
```csharp
 <OutsideHandleContainer OnClickOutside=@OnClickOutside>
    ...
    <div>Sample element</div>
    ...
</OutsideHandleContainer>

@functions{
    void OnClickOutside()
    {
        // Do stuff
    }
}
```
##### Note: If you need more method for this package, feel free to create issue on this repository.