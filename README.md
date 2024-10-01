1. Install `Tailwind.MSBuild` Nuget Package: https://www.nuget.org/packages/Tailwind.MSBuild
2. Update .csproj so that Tailwind output is written in a more conventional location for MVC5: https://github.com/ronnieoverby/MVC5Tailwind/blob/ed70cb60de016ebf1611fdcea1de4fb86782bb2a/MVC5Tailwind.csproj#L6-L8
3. Build the project to generate files in the `Properties` directory: https://github.com/ronnieoverby/MVC5Tailwind/tree/master/Properties
4. Modify tailwind.config.js so that input files are processed: https://github.com/ronnieoverby/MVC5Tailwind/blob/ed70cb60de016ebf1611fdcea1de4fb86782bb2a/Properties/tailwind.config.js#L3
5. Modify or create a new bundle that will include the Tailwind output: https://github.com/ronnieoverby/MVC5Tailwind/blob/ed70cb60de016ebf1611fdcea1de4fb86782bb2a/App_Start/BundleConfig.cs#L29-L30
6. Reference the bundle: https://github.com/ronnieoverby/MVC5Tailwind/blob/ed70cb60de016ebf1611fdcea1de4fb86782bb2a/Views/Tailwind/Index.cshtml#L12
7. Use Tailwind! https://github.com/ronnieoverby/MVC5Tailwind/blob/master/Views/Shared/TailwindSample.cshtml
