The Partial Tag Helper is used for rendering a partial view in Razor Pages and MVC apps. Consider that it:

Requires ASP.NET Core 2.1 or later.
Is an alternative to HTML Helper syntax.
Renders the partial view asynchronously.
The HTML Helper options for rendering a partial view include:


```cshtml
<partial name="Shared/_ProductPartial.cshtml" for="Product">
```

refence : https://docs.microsoft.com/en-us/aspnet/core/mvc/views/tag-helpers/built-in/partial-tag-helper?view=aspnetcore-5.0
