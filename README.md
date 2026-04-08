# L-W-Training-ASP-Example-Site

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/6f78e41a-726a-4f28-b108-5a48eeae5ae1" />

### Project structure
- Standard ASP.NET Core 8 MVC scaffold: Controllers/, Views/, Models/, wwwroot/, Program.cs, LWTraining.csproj
- .gitignore covering bin/, obj/, .vs/, and OS artefacts
- libman.json for managing client-side libraries via the LibMan CLI

### Branding (L-W Tech Training)
- **Navbar** — navbar-dark bg-primary with 🎓 L-W Tech Training brand link; nav links use text-white
- **Page title** — @ViewData["Title"] - L-W Tech Training
- **Footer** — © 2026 - L-W Tech Training
- **Home page** — hero section referencing Azure Web Apps deployment + three feature cards (Azure Deployment, ASP.NET Core MVC, L-W Tech Training)

```
<nav class="navbar navbar-expand-sm navbar-dark bg-primary ...">
    <a class="navbar-brand fw-bold" ...>🎓 L-W Tech Training</a>
    ...
</nav>
```

### Client-side libraries
Updated all vendored front-end assets to the current supported versions:

| Library	| Version |
|---|---|
| Bootstrap |	5.3.8 |
| jQuery |	3.7.1 |
| jQuery Validation |	1.22.1 |
| jQuery Validation Unobtrusive |	4.0.0 |
