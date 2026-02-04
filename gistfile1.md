<?xml version="1.0" encoding="utf-8"?>
<configuration>
  <packageSources>
    <!-- Clear any existing feeds to avoid conflicts -->
    <clear />

    <!-- Official NuGet feed for stable packages -->
    <add key="NuGet.org" value="https://api.nuget.org/v3/index.json" />

    <!-- Xamarin nightly/CI feed for pre-release builds -->
    <add key="xamarin-ci" value="https://aka.ms/xf-nightly/index.json" />

    <!-- Custom feed for your internal libraries (e.g., glass shell, dual-screen support) -->
    <add key="NeomindAI-Internal" value="https://your-private-feed-url.com/nuget" />

    <!-- Optional: another private feed for shared team packages -->
    <add key="KubuPackages" value="https://packages.kubu.io/nuget" />
  </packageSources>

  <!-- Optional: package version management -->
  <packageSourceCredentials>
    <NeomindAI-Internal>
      <add key="Username" value="YOUR_USERNAME" />
      <add key="ClearTextPassword" value="YOUR_PASSWORD" />
    </NeomindAI-Internal>
    <KubuPackages>
      <add key="Username" value="YOUR_USERNAME" />
      <add key="ClearTextPassword" value="YOUR_PASSWORD" />
    </KubuPackages>
  </packageSourceCredentials>

  <!-- Optional: disable fallback to default feeds if needed -->
  <disabledPackageSources>
    <add key="Microsoft Visual Studio Offline Packages" value="true" />
  </disabledPackageSources>
</configuration>