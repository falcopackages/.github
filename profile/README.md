## Hi there 👋🏾

> [!Important]
> If you’re a complete beginner, I wouldn’t recommend using these tools yet. There’s nothing overly complex here, but you might feel lost and frustrated with all the tools and concepts involved.
> First, get comfortable [building Django projects](https://docs.djangoproject.com/en/dev/intro/tutorial01/) with the default project structure and [deploying them to production manually on
> a Linux box](https://falco.oluwatobi.dev/guides/deployment.html). Then you can come back here and pick the ideas and tools you find interesting.

This organization is a collection of tools designed to improve the experience of Django developers, reducing friction when starting up new projects and simplifying deployment in production.

- [falco-cli](https://github.com/falcopackages/falco-cli): Start a project using the falco starter-template and keep it updated
- [starter-template](https://github.com/falcopackages/starter-template): Project starter including uv, Docker production setup, helpers for project version management, CI/CD pipelines, all your dev commands managed via a justfile, and more
- [falco (wip)](https://github.com/falcopackages/falco): A Django application that comes with commands for `CRUD` generation, a `start-app` command that auto-registers new apps, HTMX download, and more
- [falco-ui (wip)](https://github.com/falcopackages/falco-ui): Integrates [daisyui](https://daisyui.com/) for better looking HTML for CRUD, forms, and allauth templates
- [fujin (wip)](https://github.com/falcopackages/fujin): Automates the deployment of your Django project (and any project following a few prerequisites) on a Linux box while leaving you in full control of your server

> [!Note]  
> You can generate a ready-to-use Django project with falco by visiting this link: [Falco Template Repository](https://github.com/falcopackages/falco-template-repository/generate).  
> The initial project you get is not the completed version. Wait about a minute and then reload the page to see the final result.

The missing piece for me right now to consider my Django workflow perfect is a tool to better organize frontend code for larger projects, but I have a few good candidates:

- [django-cotton](github.com/wrabit/django-cotton): A component library for Django that enables you to use HTML-like tag syntax
- [django-bird (wip)](https://github.com/joshuadavidthomas/django-bird): Another component library in very early stages, but I really like the proposed API

These are my current favorites for the future of Django. If at some point we get something like Laravel's [flux](https://fluxui.dev/) for Django, that would be the cherry on top.

Here's a list of extra packages I use from time to time that don't come included in the starter-template:

- [django-simple-nav](https://github.com/westerveltco/django-simple-nav)
- [django-tables2](https://github.com/jieter/django-tables2)
- [django-pgtrigger](https://github.com/Opus10/django-pgtrigger)
- [django-eventstream](https://github.com/fanout/django-eventstream)
- [django-pgclone](https://github.com/Opus10/django-pgclone)
- [django-perf-rec](https://github.com/adamchainz/django-perf-rec)
- [coltrane](https://github.com/adamghill/coltrane)

Have any questions or suggestions? Open a new [discussion](https://github.com/orgs/falcopackages/discussions).<br>
Need help with your Django project? Feel free to reach out to [me](https://github.com/Tobi-De) at [tobidegnon@proton.me](mailto:tobidegnon@proton.me).<br>
If you find these tools helpful, consider [buying me a coffee](https://buymeacoffee.com/oluwa.tobi) to support my work! ☕
