# .NET Samples

![Markdownlint](https://github.com/dotnet/samples/workflows/Markdownlint/badge.svg)

This repo contains all the sample code that is part of any topic under
the .NET documentation. There are several different projects that
are organized in sub-folders. These sub-folders are organized similarly
to the organization of the docs for .NET. Some of the articles will have more than one sample associated with them.

The content team tracks issues for .NET documentation in the [dotnet/docs](https://github.com/dotnet/docs) and [dotnet/dotnet-api-docs](https://github.com/dotnet/dotnet-api-docs) repositories. Issues are turned off on this repository. File issues against existing samples and suggestions for new samples in those repositories. If you're not sure where, choose [dotnet/docs](https://github.com/dotnet/docs/issues). This process keeps the issues associated with the articles that explain the concepts for each sample. The best process is to file an issue from the feedback control at the bottom of each docs page:

- For existing samples, file the issue on the page with the sample.
- To suggest new samples, file the issue on the index page where you want to see the new sample.

The code in this repository represents programs that demonstrate application or library scenarios. These samples often use more than one technology, feature, or toolkit. Each sample has a readme.md file that explains the sample and links to resources for more information.

Samples should be buildable projects. Those projects should build and
run on the widest set of platforms possible for the given sample. In practice, that means building .NET Core-based console applications where possible. Samples that are specific to the web or a UI framework should add those tools as needed. Examples include web applications, mobile apps, WPF or WinForms apps, and so on.

We are working toward having a CI system in place for all code. When you make any updates to samples, make sure each update is part of a buildable
project. Ideally, add tests for correctness on samples as well.
