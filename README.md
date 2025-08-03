# Jumia
├── Jumia-Api
    ├── Jumia-Api.Api
    │   ├── Controllers
    │   │   ├── AddressController.cs
    │   │   ├── AiQueryController.cs
    │   │   ├── AuthController.cs
    │   │   ├── CartController.cs
    │   │   ├── CategoriesController.cs
    │   │   ├── ChatController.cs
    │   │   ├── CompaignController.cs
    │   │   ├── CouponController.cs
    │   │   ├── OrderController.cs
    │   │   ├── PaymentController.cs
    │   │   ├── ProductController.cs
    │   │   ├── RatingController.cs
    │   │   ├── RecommendationController.cs
    │   │   ├── SellerController.cs
    │   │   ├── TestController.cs
    │   │   ├── UserController.cs
    │   │   └── WishlistController.cs
    │   ├── DependencyInjection
    │   │   ├── Application
    │   │   │   └── ApplicationServicesRegistraion.cs
    │   │   ├── Domain
    │   │   │   └── DomainServicesRegistraion.cs
    │   │   └── Infrastructure
    │   │   │   └── InfrastructureServicesRegistraion.cs
    │   ├── Jumia-Api.Api.csproj
    │   ├── Jumia-Api.Api.csproj.user
    │   ├── Jumia-Api.Api.http
    │   ├── Program.cs
    │   ├── Properties
    │   │   └── launchSettings.json
    │   ├── Results
    │   │   ├── AuthResult.cs
    │   │   └── Result.cs
    │   ├── appsettings.Development.json
    │   ├── appsettings.json
    │   ├── bin
    │   │   └── Debug
    │   │   │   └── net9.0
    │   │   │       ├── Ardalis.GuardClauses.dll
    │   │   │       ├── AutoMapper.dll
    │   │   │       ├── Azure.Core.dll
    │   │   │       ├── Azure.Identity.dll
    │   │   │       ├── Flurl.dll
    │   │   │       ├── Google.Protobuf.dll
    │   │   │       ├── Grpc.Core.Api.dll
    │   │   │       ├── Grpc.Net.Client.dll
    │   │   │       ├── Grpc.Net.Common.dll
    │   │   │       ├── Humanizer.dll
    │   │   │       ├── Jumia-Api.Api.deps.json
    │   │   │       ├── Jumia-Api.Api.dll
    │   │   │       ├── Jumia-Api.Api.exe
    │   │   │       ├── Jumia-Api.Api.pdb
    │   │   │       ├── Jumia-Api.Api.runtimeconfig.json
    │   │   │       ├── Jumia-Api.Api.staticwebassets.endpoints.json
    │   │   │       ├── Jumia-Api.Api.staticwebassets.runtime.json
    │   │   │       ├── Jumia-Api.Application.dll
    │   │   │       ├── Jumia-Api.Application.pdb
    │   │   │       ├── Jumia-Api.Domain.dll
    │   │   │       ├── Jumia-Api.Domain.pdb
    │   │   │       ├── Jumia-Api.Infrastructure.dll
    │   │   │       ├── Jumia-Api.Infrastructure.pdb
    │   │   │       ├── LatoFont
    │   │   │           ├── Lato-Black.ttf
    │   │   │           ├── Lato-BlackItalic.ttf
    │   │   │           ├── Lato-Bold.ttf
    │   │   │           ├── Lato-BoldItalic.ttf
    │   │   │           ├── Lato-ExtraBold.ttf
    │   │   │           ├── Lato-ExtraBoldItalic.ttf
    │   │   │           ├── Lato-ExtraLight.ttf
    │   │   │           ├── Lato-ExtraLightItalic.ttf
    │   │   │           ├── Lato-Italic.ttf
    │   │   │           ├── Lato-Light.ttf
    │   │   │           ├── Lato-LightItalic.ttf
    │   │   │           ├── Lato-Medium.ttf
    │   │   │           ├── Lato-MediumItalic.ttf
    │   │   │           ├── Lato-Regular.ttf
    │   │   │           ├── Lato-SemiBold.ttf
    │   │   │           ├── Lato-SemiBoldItalic.ttf
    │   │   │           ├── Lato-Thin.ttf
    │   │   │           ├── Lato-ThinItalic.ttf
    │   │   │           └── OFL.txt
    │   │   │       ├── Microsoft.AspNetCore.Authentication.JwtBearer.dll
    │   │   │       ├── Microsoft.AspNetCore.Cryptography.Internal.dll
    │   │   │       ├── Microsoft.AspNetCore.Cryptography.KeyDerivation.dll
    │   │   │       ├── Microsoft.AspNetCore.Identity.EntityFrameworkCore.dll
    │   │   │       ├── Microsoft.AspNetCore.OpenApi.dll
    │   │   │       ├── Microsoft.Bcl.AsyncInterfaces.dll
    │   │   │       ├── Microsoft.Build.Locator.dll
    │   │   │       ├── Microsoft.CodeAnalysis.CSharp.Workspaces.dll
    │   │   │       ├── Microsoft.CodeAnalysis.CSharp.dll
    │   │   │       ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.dll
    │   │   │       ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.dll
    │   │   │       ├── Microsoft.CodeAnalysis.Workspaces.dll
    │   │   │       ├── Microsoft.CodeAnalysis.dll
    │   │   │       ├── Microsoft.Data.SqlClient.dll
    │   │   │       ├── Microsoft.EntityFrameworkCore.Abstractions.dll
    │   │   │       ├── Microsoft.EntityFrameworkCore.Design.dll
    │   │   │       ├── Microsoft.EntityFrameworkCore.Relational.dll
    │   │   │       ├── Microsoft.EntityFrameworkCore.SqlServer.dll
    │   │   │       ├── Microsoft.EntityFrameworkCore.dll
    │   │   │       ├── Microsoft.Extensions.AI.Abstractions.dll
    │   │   │       ├── Microsoft.Extensions.Caching.Abstractions.dll
    │   │   │       ├── Microsoft.Extensions.Caching.Memory.dll
    │   │   │       ├── Microsoft.Extensions.Configuration.Abstractions.dll
    │   │   │       ├── Microsoft.Extensions.DependencyInjection.Abstractions.dll
    │   │   │       ├── Microsoft.Extensions.DependencyInjection.dll
    │   │   │       ├── Microsoft.Extensions.DependencyModel.dll
    │   │   │       ├── Microsoft.Extensions.Diagnostics.Abstractions.dll
    │   │   │       ├── Microsoft.Extensions.FileProviders.Abstractions.dll
    │   │   │       ├── Microsoft.Extensions.Hosting.Abstractions.dll
    │   │   │       ├── Microsoft.Extensions.Http.Polly.dll
    │   │   │       ├── Microsoft.Extensions.Identity.Core.dll
    │   │   │       ├── Microsoft.Extensions.Identity.Stores.dll
    │   │   │       ├── Microsoft.Extensions.Logging.Abstractions.dll
    │   │   │       ├── Microsoft.Extensions.Logging.dll
    │   │   │       ├── Microsoft.Extensions.Options.dll
    │   │   │       ├── Microsoft.Extensions.Primitives.dll
    │   │   │       ├── Microsoft.Identity.Client.Extensions.Msal.dll
    │   │   │       ├── Microsoft.Identity.Client.dll
    │   │   │       ├── Microsoft.IdentityModel.Abstractions.dll
    │   │   │       ├── Microsoft.IdentityModel.JsonWebTokens.dll
    │   │   │       ├── Microsoft.IdentityModel.Logging.dll
    │   │   │       ├── Microsoft.IdentityModel.Protocols.OpenIdConnect.dll
    │   │   │       ├── Microsoft.IdentityModel.Protocols.dll
    │   │   │       ├── Microsoft.IdentityModel.Tokens.dll
    │   │   │       ├── Microsoft.OpenApi.dll
    │   │   │       ├── Microsoft.SqlServer.Server.dll
    │   │   │       ├── Microsoft.Win32.SystemEvents.dll
    │   │   │       ├── Mono.TextTemplating.dll
    │   │   │       ├── Newtonsoft.Json.dll
    │   │   │       ├── OllamaSharp.dll
    │   │   │       ├── Polly.Extensions.Http.dll
    │   │   │       ├── Polly.dll
    │   │   │       ├── Qdrant.Client.dll
    │   │   │       ├── QuestPDF.dll
    │   │   │       ├── SendGrid.dll
    │   │   │       ├── StarkbankEcdsa.dll
    │   │   │       ├── Swashbuckle.AspNetCore.Annotations.dll
    │   │   │       ├── Swashbuckle.AspNetCore.Swagger.dll
    │   │   │       ├── Swashbuckle.AspNetCore.SwaggerGen.dll
    │   │   │       ├── Swashbuckle.AspNetCore.SwaggerUI.dll
    │   │   │       ├── SymSpell.dll
    │   │   │       ├── System.ClientModel.dll
    │   │   │       ├── System.CodeDom.dll
    │   │   │       ├── System.Composition.AttributedModel.dll
    │   │   │       ├── System.Composition.Convention.dll
    │   │   │       ├── System.Composition.Hosting.dll
    │   │   │       ├── System.Composition.Runtime.dll
    │   │   │       ├── System.Composition.TypedParts.dll
    │   │   │       ├── System.Configuration.ConfigurationManager.dll
    │   │   │       ├── System.Drawing.Common.dll
    │   │   │       ├── System.Formats.Asn1.dll
    │   │   │       ├── System.IdentityModel.Tokens.Jwt.dll
    │   │   │       ├── System.Memory.Data.dll
    │   │   │       ├── System.Runtime.Caching.dll
    │   │   │       ├── System.Security.Cryptography.ProtectedData.dll
    │   │   │       ├── System.Security.Permissions.dll
    │   │   │       ├── System.Text.Json.dll
    │   │   │       ├── System.Windows.Extensions.dll
    │   │   │       ├── TimeZoneConverter.dll
    │   │   │       ├── Xdot.Paymob.CashIn.DependencyInjection.dll
    │   │   │       ├── Xdot.Paymob.CashIn.dll
    │   │   │       ├── appsettings.Development.json
    │   │   │       ├── appsettings.json
    │   │   │       ├── cs
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │   │       ├── de
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │   │       ├── es
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │   │       ├── fr
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │   │       ├── it
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │   │       ├── ja
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │   │       ├── ko
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │   │       ├── pl
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │   │       ├── pt-BR
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │   │       ├── ru
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │   │       ├── runtimes
    │   │   │           ├── linux-arm64
    │   │   │           │   └── native
    │   │   │           │   │   ├── libQuestPdfSkia.so
    │   │   │           │   │   ├── libcrypto.so
    │   │   │           │   │   ├── libjpeg.so.8
    │   │   │           │   │   └── libqpdf.so
    │   │   │           ├── linux-musl-x64
    │   │   │           │   └── native
    │   │   │           │   │   ├── libQuestPdfSkia.so
    │   │   │           │   │   ├── libcrypto.so
    │   │   │           │   │   ├── libjpeg.so.8
    │   │   │           │   │   └── libqpdf.so
    │   │   │           ├── linux-x64
    │   │   │           │   └── native
    │   │   │           │   │   ├── libQuestPdfSkia.so
    │   │   │           │   │   ├── libcrypto.so
    │   │   │           │   │   ├── libjpeg.so.8
    │   │   │           │   │   └── libqpdf.so
    │   │   │           ├── osx-arm64
    │   │   │           │   └── native
    │   │   │           │   │   ├── libQuestPdfSkia.dylib
    │   │   │           │   │   ├── libcrypto.dylib
    │   │   │           │   │   ├── libjpeg.dylib
    │   │   │           │   │   └── libqpdf.dylib
    │   │   │           ├── osx-x64
    │   │   │           │   └── native
    │   │   │           │   │   ├── libQuestPdfSkia.dylib
    │   │   │           │   │   ├── libcrypto.dylib
    │   │   │           │   │   ├── libjpeg.dylib
    │   │   │           │   │   └── libqpdf.dylib
    │   │   │           ├── unix
    │   │   │           │   └── lib
    │   │   │           │   │   └── net6.0
    │   │   │           │   │       ├── Microsoft.Data.SqlClient.dll
    │   │   │           │   │       └── System.Drawing.Common.dll
    │   │   │           ├── win-arm
    │   │   │           │   └── native
    │   │   │           │   │   └── Microsoft.Data.SqlClient.SNI.dll
    │   │   │           ├── win-arm64
    │   │   │           │   └── native
    │   │   │           │   │   └── Microsoft.Data.SqlClient.SNI.dll
    │   │   │           ├── win-x64
    │   │   │           │   └── native
    │   │   │           │   │   ├── Microsoft.Data.SqlClient.SNI.dll
    │   │   │           │   │   ├── QuestPdfSkia.dll
    │   │   │           │   │   ├── libgcc_s_seh-1.dll
    │   │   │           │   │   ├── libstdc++-6.dll
    │   │   │           │   │   ├── libwinpthread-1.dll
    │   │   │           │   │   └── qpdf.dll
    │   │   │           ├── win-x86
    │   │   │           │   └── native
    │   │   │           │   │   ├── Microsoft.Data.SqlClient.SNI.dll
    │   │   │           │   │   ├── QuestPdfSkia.dll
    │   │   │           │   │   ├── libgcc_s_dw2-1.dll
    │   │   │           │   │   ├── libstdc++-6.dll
    │   │   │           │   │   ├── libwinpthread-1.dll
    │   │   │           │   │   └── qpdf.dll
    │   │   │           └── win
    │   │   │           │   └── lib
    │   │   │           │       └── net6.0
    │   │   │           │           ├── Microsoft.Data.SqlClient.dll
    │   │   │           │           ├── Microsoft.Win32.SystemEvents.dll
    │   │   │           │           ├── System.Drawing.Common.dll
    │   │   │           │           ├── System.Runtime.Caching.dll
    │   │   │           │           ├── System.Security.Cryptography.ProtectedData.dll
    │   │   │           │           └── System.Windows.Extensions.dll
    │   │   │       ├── tr
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │   │       ├── zh-Hans
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   │   │       └── zh-Hant
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.Workspaces.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.CSharp.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.MSBuild.BuildHost.resources.dll
    │   │   │           ├── Microsoft.CodeAnalysis.Workspaces.resources.dll
    │   │   │           └── Microsoft.CodeAnalysis.resources.dll
    │   ├── obj
    │   │   ├── Debug
    │   │   │   └── net9.0
    │   │   │   │   ├── .NETCoreApp,Version=v9.0.AssemblyAttributes.cs
    │   │   │   │   ├── ApiEndpoints.json
    │   │   │   │   ├── EndpointInfo
    │   │   │   │       ├── Jumia-Api.Api.OpenApiFiles.cache
    │   │   │   │       └── Jumia-Api.Api.json
    │   │   │   │   ├── Jumia-Ap.F96EEDA2.Up2Date
    │   │   │   │   ├── Jumia-Api.Api.AssemblyInfo.cs
    │   │   │   │   ├── Jumia-Api.Api.AssemblyInfoInputs.cache
    │   │   │   │   ├── Jumia-Api.Api.GeneratedMSBuildEditorConfig.editorconfig
    │   │   │   │   ├── Jumia-Api.Api.GlobalUsings.g.cs
    │   │   │   │   ├── Jumia-Api.Api.MvcApplicationPartsAssemblyInfo.cache
    │   │   │   │   ├── Jumia-Api.Api.MvcApplicationPartsAssemblyInfo.cs
    │   │   │   │   ├── Jumia-Api.Api.assets.cache
    │   │   │   │   ├── Jumia-Api.Api.csproj.AssemblyReference.cache
    │   │   │   │   ├── Jumia-Api.Api.csproj.BuildWithSkipAnalyzers
    │   │   │   │   ├── Jumia-Api.Api.csproj.CoreCompileInputs.cache
    │   │   │   │   ├── Jumia-Api.Api.csproj.FileListAbsolute.txt
    │   │   │   │   ├── Jumia-Api.Api.dll
    │   │   │   │   ├── Jumia-Api.Api.genruntimeconfig.cache
    │   │   │   │   ├── Jumia-Api.Api.pdb
    │   │   │   │   ├── Jumia-Api.Api.sourcelink.json
    │   │   │   │   ├── apphost.exe
    │   │   │   │   ├── ref
    │   │   │   │       └── Jumia-Api.Api.dll
    │   │   │   │   ├── refint
    │   │   │   │       └── Jumia-Api.Api.dll
    │   │   │   │   ├── rjimswa.dswa.cache.json
    │   │   │   │   ├── rjsmcshtml.dswa.cache.json
    │   │   │   │   ├── rjsmrazor.dswa.cache.json
    │   │   │   │   ├── rpswa.dswa.cache.json
    │   │   │   │   ├── staticwebassets.build.endpoints.json
    │   │   │   │   ├── staticwebassets.build.json
    │   │   │   │   ├── staticwebassets.build.json.cache
    │   │   │   │   ├── staticwebassets.development.json
    │   │   │   │   ├── staticwebassets.references.upToDateCheck.txt
    │   │   │   │   ├── staticwebassets.removed.txt
    │   │   │   │   └── staticwebassets.upToDateCheck.txt
    │   │   ├── Jumia-Api.Api.csproj.nuget.dgspec.json
    │   │   ├── Jumia-Api.Api.csproj.nuget.g.props
    │   │   ├── Jumia-Api.Api.csproj.nuget.g.targets
    │   │   ├── project.assets.json
    │   │   └── project.nuget.cache
    │   └── wwwroot
    │   │   ├── symSpell
    │   │       └── frequency_dictionary_en_82_765.txt
    │   │   └── uploads
    │   │       ├── products
    │   │           ├── 00133fbf-c024-43b5-89a5-e8fd5b443f71_7.jpg.jpeg
    │   │           ├── 004c1201-de35-450a-9689-2f425987136d_2.jpg.jpeg
    │   │           ├── 04493d7a-a862-444f-8045-d16bfe1fc92c_1 (23).jpeg
    │   │           ├── 05801dc9-4994-4a58-8c93-6c24197b0369_3 (16).jpeg
    │   │           ├── 07c4551c-17f6-4982-b35e-b92fa9ddc8c9_1.jpg.jpeg
    │   │           ├── 0988e6b2-2499-4808-91a0-4fa088efa008_1 (2).jpeg
    │   │           ├── 09f583bd-fdd9-4ad5-afdf-49cb6f96d8c8_1 (23).jpeg
    │   │           ├── 0a7e455e-3fb7-4758-9ff3-72c4665f1ace_9.jpg.jpeg
    │   │           ├── 0b05aa4c-0a9d-4d48-846e-fcc9f1625204_7.jpg.jpeg
    │   │           ├── 0b077c15-b040-4188-9b53-7a97fb7537ca_4 (1).jpeg
    │   │           ├── 0b569bb2-3370-47ce-ba31-0181f29e3937_1 (20).jpeg
    │   │           ├── 0bace1df-c9b1-460c-aa2c-7a831ba86367_4.jpg.jpeg
    │   │           ├── 0ca6aabc-fd91-46ec-a26f-85dbae44db76_3.jpg.jpeg
    │   │           ├── 0cf450d0-6076-48c5-8477-66f90cc4abb2_1.jpg
    │   │           ├── 0d0c0269-7eb7-46fd-b682-997f8b3e2e51_3 (10).jpeg
    │   │           ├── 0d85b8a2-bd11-4ddf-a811-95fcf18566b0_1 (26).jpeg
    │   │           ├── 0f2fafab-0eb1-49d1-9edc-2ca528fc8505_agilemethedology.jpg
    │   │           ├── 0fd0aec6-9a9c-481a-90b9-daef74dc5d84_1 (2).jpeg
    │   │           ├── 105c0406-56ad-47b7-b99d-c68ef8ec5184_3.jpeg
    │   │           ├── 115b2dea-59cc-4969-a684-5a1358bd9e2b_3 (7).jpeg
    │   │           ├── 1217ee2f-3f3e-49b9-aa90-afede9fa90ba_agilemethedology.jpg
    │   │           ├── 1246e453-65ef-4ff1-9545-2e8d0d39e2c0_7.jpeg
    │   │           ├── 1697727f-c274-4f0f-b999-9e88110b3c32_1 (9).jpeg
    │   │           ├── 179fd2d7-f88f-4bdc-a4d7-a0f7d9e6ef23_2 (5).jpeg
    │   │           ├── 17af5dd1-a6f2-43fe-8e3f-1d85ca5ed1aa_1 (21).jpeg
    │   │           ├── 17c904a4-090a-4c38-9fa2-00c935b21c99_4.jpg.jpeg
    │   │           ├── 18efbd77-886d-45ec-9788-c328b679ce83_3 (4).jpeg
    │   │           ├── 192d84a9-3f55-479d-b3a3-8757486f88a8_1.jpeg
    │   │           ├── 1c1c2c10-9b2f-4985-8a3a-b508ef54079c_1.jpg
    │   │           ├── 1d1cb6fd-7bce-4d64-9897-b7aa9288bb09_2.jpg.jpeg
    │   │           ├── 1dfeb7b0-7ff2-4b74-b187-a5cd0fe6cd61_1 (2).jpeg
    │   │           ├── 1e35b9ae-3a5a-4065-a4dc-dfb366d28efe_2.jpg.jpeg
    │   │           ├── 1f0f56a3-b9be-4756-8065-9100a0674911_5 (1).jpeg
    │   │           ├── 1f65c3d1-3be3-4287-b822-4a9212e155ec_2 (16).jpeg
    │   │           ├── 1fd9ec97-772b-4202-9003-b9ce6f53d372_5 (3).jpeg
    │   │           ├── 21ec8649-a585-4559-b98b-a15723ce4283_5 (5).jpeg
    │   │           ├── 222b8113-6078-4772-9fa9-5107a8891831_2 (16).jpeg
    │   │           ├── 22bc8753-53ae-430e-8860-541798d44883_1 (23).jpeg
    │   │           ├── 23ccac94-d37f-4e5c-882b-cef3f5bba9f9_4.jpeg
    │   │           ├── 26fce46a-f8dc-4c49-8780-7d6b659e0ac3_4.jpg.jpeg
    │   │           ├── 27019853-5274-4b7b-9b4e-59d6f73d41a6_1.jpg
    │   │           ├── 2709e838-a3ed-4b68-87b8-99bd256415f2_3.jpg.jpeg
    │   │           ├── 27fb3382-5645-4213-80eb-5a5f94ebeffd_agilemethedology.jpg
    │   │           ├── 2855c1c5-5908-427f-a2bb-d75c4c73f4c6_1 (4).jpeg
    │   │           ├── 287a1d7a-2f36-46ed-a2ae-cc68f29ab6ae_2.jpg.jpeg
    │   │           ├── 28eed02b-2ac8-4649-b770-511180aae932_6.jpg.jpeg
    │   │           ├── 2a94702a-1cf1-4a4b-87e4-dad410c3659b_3 (2).jpeg
    │   │           ├── 2b3e133a-7ff3-48dc-89c3-9ba518c19e9b_1 (28).jpeg
    │   │           ├── 2c08afaf-704f-4a02-af9e-61977120f558_1.jpg
    │   │           ├── 2c70be55-0be3-448e-8218-694570ef2a5f_1.jpeg
    │   │           ├── 2cc77956-5490-4527-86e3-582e54bb1fbb_2 (6).jpeg
    │   │           ├── 2f2a111b-eafb-4875-9a36-bd574cab5ca1_1.jpg.jpeg
    │   │           ├── 2ff7b5dd-f903-43ef-96b0-b273e05833d7_1 (2).jpeg
    │   │           ├── 32fbadda-b3d5-4e49-b740-4f827b78ee85_1 (45).jpeg
    │   │           ├── 330359f2-4a63-45f4-ac76-7d59a38dbb85_493837885_122152752836558855_6467953089869829267_n.jpg
    │   │           ├── 3346cf05-e636-4cc8-9c5c-352a80a5bd77_2.jpg.jpeg
    │   │           ├── 340373f8-a3b7-435d-b5e2-2eec87e9b942_1 (22).jpeg
    │   │           ├── 3527280f-0911-422b-9c45-4ce2917f73d0_1.jpeg
    │   │           ├── 36431734-6280-49c1-acb8-5178b289baf7_3 (5).jpeg
    │   │           ├── 36eb84ea-975f-4d06-bd6b-1c8a1d100bf8_4 (9).jpeg
    │   │           ├── 388a5d80-f318-4318-8632-bfb3ad08d671_2.jpg.jpeg
    │   │           ├── 3b0c575f-7d10-4b0b-9357-16b46905dd04_1.jpg
    │   │           ├── 3b37f2d8-e554-4315-8ad3-6b2e7f28f876_1.jpeg
    │   │           ├── 41c7a071-9c2d-470b-bdee-c1b18d5e690d_1 (23).jpeg
    │   │           ├── 423129ec-818e-4d47-aece-f7457d3c2039_1 (25).jpeg
    │   │           ├── 43535886-3940-4a92-9aca-b058ec6023b9_10.jpg.jpeg
    │   │           ├── 43cadbf2-6a3d-4714-abc5-7e0b55e1f908_2 (3).jpeg
    │   │           ├── 46c0564a-1a49-4eda-b922-06233ddef904_3.jpg.jpeg
    │   │           ├── 46db4580-e147-4acf-ae95-54327b078bab_1.jpg.jpeg
    │   │           ├── 47107ba4-b11d-4567-ab7a-044cbe3e6215_4 (12).jpeg
    │   │           ├── 478c583a-4ad9-4cd0-a0a9-25a92c984e15_1.jpeg
    │   │           ├── 47c13d59-93bb-4cbd-820c-04bda50d2014_6.jpg.jpeg
    │   │           ├── 47c9eac5-f2b0-4c1d-94dd-a856ceb2c494_8.jpg.jpeg
    │   │           ├── 4b42cfcc-2b42-4e3e-8a68-c5d736be480e_4 (6).jpeg
    │   │           ├── 4b5ee8bb-e925-425a-a9f1-d65b1d09f821_2 (2).jpeg
    │   │           ├── 4e04fb85-75b0-4232-85fa-693c2a93c824_2 (12).jpeg
    │   │           ├── 4e229528-1760-4a06-9eb3-cdabfe076f40_1 (25).jpeg
    │   │           ├── 4e9a33f7-fd64-4b56-85d4-0a3d950020c6_1.jpeg
    │   │           ├── 50c6b560-8209-4c4a-a235-dc45d7a557b1_2 (3).jpeg
    │   │           ├── 51899e96-7015-4d65-a3c8-a83f882befd4_1 (18).jpeg
    │   │           ├── 5397e6d1-5688-4dec-b164-32efec7f3aef_1.jpeg
    │   │           ├── 5415b5d5-f761-42fd-bb62-df0f0a400de8_1 (45).jpeg
    │   │           ├── 563fe0af-204b-459a-9b37-dcd38399cd6c_3 (11).jpeg
    │   │           ├── 5688b60b-be58-4cb1-b511-baff1919cb15_4 (1).jpeg
    │   │           ├── 5c2762f9-f3e2-4721-930c-983fd39098f2_4 (11).jpeg
    │   │           ├── 5c9d37b5-8ca1-4ac0-a99d-4c948643b1c9_1.jpg.jpeg
    │   │           ├── 5db3fecf-eb91-4ec2-b756-9201995e64d3_1 (11).jpeg
    │   │           ├── 5f10437d-2d2b-4ca8-8ce0-32548d7e6195_4.jpg.jpeg
    │   │           ├── 60bf18f0-15c9-4075-bbfc-2ed4c5aaccf9_3 (1).jpeg
    │   │           ├── 617c5c64-e730-4960-aa73-fe3e3ca9dff9_1 (30).jpeg
    │   │           ├── 630368c0-b2aa-4fc1-8467-0744340d8779_Screenshot 2025-07-23 171241.png
    │   │           ├── 63ae841e-a1f4-46d0-8f2c-487fc1e5bd73_1.jpg.jpeg
    │   │           ├── 664fd609-7a45-4849-b444-c5dff1d71886_7.jpg.jpeg
    │   │           ├── 67653bbd-35fe-4972-ad98-bbb0c63cf760_4 (4).jpeg
    │   │           ├── 678a70a6-a3d3-4139-99aa-7c6ab47b6608_1 (1).jpeg
    │   │           ├── 6827c9cf-d907-4b92-89a7-87f335e2dd04_1 (29).jpeg
    │   │           ├── 69922c5c-0711-4f81-bea5-6f10dd95f190_2.jpg.jpeg
    │   │           ├── 69b81a5a-04ab-4f9e-b0e5-cd48c606636a_1 (24).jpeg
    │   │           ├── 6c3919d0-5050-4a03-be0d-6f2e1cfbfacd_1 (15).jpeg
    │   │           ├── 6e898fb2-be39-42fd-89e0-c53328a574c5_1 (34).jpeg
    │   │           ├── 6feeb82d-b264-4932-bc53-52012526d349_1.jpeg
    │   │           ├── 70a1bfed-1f2c-4897-b81a-bddfedd8b4da_1.jpg
    │   │           ├── 718910e4-9cd2-4da1-8558-4a961d6f8fd9_5.jpg.jpeg
    │   │           ├── 7331178a-92b3-40a9-8deb-279c94ce16b2_2 (16).jpeg
    │   │           ├── 7349459c-9da0-48f1-83dc-34918dfb3309_2.jpg.jpeg
    │   │           ├── 736b1cd5-1eac-40b9-a6bb-050f31fc1a72_7.jpg.jpeg
    │   │           ├── 751d86f0-2e4e-4d8d-8035-d39f4b116260_1 (44).jpeg
    │   │           ├── 75b8fff2-eb03-41a4-a75b-db2c307d899b_2 (2).jpeg
    │   │           ├── 7649e9f4-d50c-4cc2-a942-0597c1ebabf9_1.jpeg
    │   │           ├── 771f5a40-a7e0-4040-a9ac-8d27164ffbe7_3 (15).jpeg
    │   │           ├── 7771ab28-3e56-4c52-a2bb-5f08525a2d5a_1 (2).jpeg
    │   │           ├── 77c876af-a500-4af7-8f40-99b2a7a9840c_3 (13).jpeg
    │   │           ├── 79329dc2-6a92-4a21-805f-eb1c1d62314c_1 (12).jpeg
    │   │           ├── 7b10a313-d1bd-470d-b89b-16e48ef84758_7.jpg.jpeg
    │   │           ├── 7b5acbd2-12a7-4e5d-9ad4-71b4b6258ab2_1 (36).jpeg
    │   │           ├── 7b68b1fe-8837-4d1f-a18b-9f85562fa92c_1.jpeg
    │   │           ├── 7d3bca5c-13b1-4485-987e-5bca6cafd78b_1 (23).jpeg
    │   │           ├── 7ea84dc2-c3dc-457e-a239-f06770a702a0_2.jpg.jpeg
    │   │           ├── 7f27ad2a-36c4-459e-9f96-d26906337686_3 (3).jpeg
    │   │           ├── 7fcb8996-63b9-41d0-a8ce-5d84dab0f81c_1 (32).jpeg
    │   │           ├── 807bb596-d9e6-4262-9529-9ccee5e429a5_1 (24).jpeg
    │   │           ├── 81c6feb2-20fa-4729-b673-6b7366e83ad4_5 (7).jpeg
    │   │           ├── 829a0148-ee1d-4691-99ea-b48c38615805_5.jpg.jpeg
    │   │           ├── 82d0f562-d824-48c5-9097-df3a5d53d524_1.jpg
    │   │           ├── 8513ea0a-00ae-47b2-a017-ba7e75e75e42_6.jpeg
    │   │           ├── 855f8afb-5d73-484e-ab8e-eb22117a92ef_1 (1).jpeg
    │   │           ├── 8621fc9d-f64b-41c5-a770-ce292f5a2414_1.jpeg
    │   │           ├── 881e5713-752f-486b-9ba8-62114bbbca67_2 (9).jpeg
    │   │           ├── 88390435-0dbb-4d79-a2f1-bac1e5971b1d_2 (16).jpeg
    │   │           ├── 8927ba8c-792c-4e83-8565-3566064f6f04_1 (40).jpeg
    │   │           ├── 8a1413a5-b241-49b5-86d9-eb949f07ad91_Screenshot 2025-07-23 171241.png
    │   │           ├── 8c7f248a-249d-4e4d-ab15-f776a2239ae7_2 (3).jpeg
    │   │           ├── 8dfcda98-8db9-4be5-b60c-d72315e44eec_7.jpg.jpeg
    │   │           ├── 8e0b47e6-f2fc-4050-a1c7-91bb767728db_1.jpg
    │   │           ├── 91f3d3a1-bd6e-4581-8908-c2e9d3cbffb1_1 (41).jpeg
    │   │           ├── 945b5a18-57c3-46c9-8371-36b16133ec14_2.jpg.jpeg
    │   │           ├── 95120cea-35cc-4a2e-9b9e-966dd5a63674_1.jpeg
    │   │           ├── 95f199bd-c93c-4498-8580-5f2841d341cf_1.jpeg
    │   │           ├── 97420fc4-83d2-486d-8e7c-3af06456ad66_1.jpg
    │   │           ├── 98520132-3aaa-4e20-a6ec-4ef1669f2b0d_5.jpg.jpeg
    │   │           ├── 9a49d56b-4f22-4719-898c-8c008ce8aeb3_5.jpeg
    │   │           ├── 9abd70bb-9976-458e-b6bf-2fff49c40164_1 (26).jpeg
    │   │           ├── 9ac295dd-9f8e-44e6-a8f1-f9d44c8247ed_1.jpg.jpeg
    │   │           ├── 9bb28c24-f14a-4eba-8cbf-bffd73b1c729_3.jpg.jpeg
    │   │           ├── 9bd736a5-0219-4b10-9800-161b82c7b0ca_1 (14).jpeg
    │   │           ├── 9d851744-39a3-4041-a518-ba2bcda43548_1.jpeg
    │   │           ├── a18c58e6-bbb2-4713-a0aa-14a7670e5609_1 (35).jpeg
    │   │           ├── a3729d17-ccd6-4553-9a66-8dfcf4248e6d_4 (13).jpeg
    │   │           ├── a444b2b1-4281-4455-9da4-ff9120aa2b86_1 (2).jpeg
    │   │           ├── a4698d6b-c51b-4669-959e-3c743e26339e_1.jpg
    │   │           ├── a59ce85b-57f1-43ec-9065-baf4b48d4ff3_1 (3).jpeg
    │   │           ├── a7bdf422-66ed-4ed9-aca4-ca1e53f7b96e_1 (7).jpeg
    │   │           ├── a8eb4f0a-f043-4ec2-a993-b7db5ee5d976_1 (42).jpeg
    │   │           ├── ab887911-910f-4aae-a619-bbe19e05435a_3.jpeg
    │   │           ├── b04d7e55-90f8-49cc-8519-30ea377b69ab_3.jpg.jpeg
    │   │           ├── b0738777-679e-427b-83a1-1d77b95e2ea7_9.jpg.jpeg
    │   │           ├── b09dedee-8cd5-4bd2-8282-832c5a0ca961_4 (1).jpeg
    │   │           ├── b29727eb-c348-4093-9a83-9580ae11e84c_493837885_122152752836558855_6467953089869829267_n.jpg
    │   │           ├── b2f6ee34-6b74-4278-a924-d0732e013d82_2 (2).jpeg
    │   │           ├── b46b1941-3828-48e4-858e-822003580397_3 (6).jpeg
    │   │           ├── b721896c-73c2-4b7e-864f-62b72c85154f_493837885_122152752836558855_6467953089869829267_n.jpg
    │   │           ├── b78acce6-02b2-4fa3-a235-f966c0259f03_3 (9).jpeg
    │   │           ├── b7b4115f-1fce-4da4-be07-abc44b482132_1.jpeg
    │   │           ├── b98b157a-2759-461a-b31c-40a23f58daf8_1.jpg.jpeg
    │   │           ├── ba14936e-e5d8-42cc-860a-975b3d884e25_1 (6).jpeg
    │   │           ├── bac15379-e69e-40d7-9fa1-7b71126626a3_5.jpg.jpeg
    │   │           ├── bee62339-15a6-4b42-b061-f3ba0d2f461d_1.jpeg
    │   │           ├── bf163961-8da6-4c2d-8ccd-2c9311a7aa92_1.jpeg
    │   │           ├── bf1b8b47-edb2-4da4-9ba4-84382db10929_3 (8).jpeg
    │   │           ├── bffc45bf-3ccb-49a4-a93a-9116bb8ad62d_4 (5).jpeg
    │   │           ├── c03e169b-ee3e-4213-a8aa-3619f9cb2736_1 (2).jpeg
    │   │           ├── c0a22371-0f32-4c4f-a224-75e764822d32_1 (13).jpeg
    │   │           ├── c1156273-6fbb-4673-bc90-fc965430169e_1.jpeg
    │   │           ├── c1aa75a2-e4e8-42c9-9799-d84f55753670_1.jpg.jpeg
    │   │           ├── c1e5bb98-13f4-4c7d-98f9-c6afa852d02e_1.jpg
    │   │           ├── c31e6608-b682-4575-9aad-5fad4b7a5a20_1 (10).jpeg
    │   │           ├── c35ea3b0-21e3-46cc-b0db-7fd7b09c9359_1.jpeg
    │   │           ├── c3b88573-30f2-4481-892c-d74085a4409a_8.jpg.jpeg
    │   │           ├── c439cc47-b54a-4fcb-ba06-cf39cbfc7e78_2.jpg.jpeg
    │   │           ├── c52c6e0a-d8ef-4fb7-ad4c-dde1b355fd85_5.jpg.jpeg
    │   │           ├── c5c20cd8-b674-47d0-859b-2ff7255ee4dd_3 (14).jpeg
    │   │           ├── c8d1fd18-0889-42aa-b73d-255b4e0c91e4_1.jpeg
    │   │           ├── cba488f7-22a6-42af-bcc9-9c11367c045f_493837885_122152752836558855_6467953089869829267_n.jpg
    │   │           ├── cc637fbc-9924-4b6f-947c-f53c66dc1036_1 (31).jpeg
    │   │           ├── cd6368cc-f6bb-4fa0-818a-b3dae236d968_1 (17).jpeg
    │   │           ├── ce2928cc-25b1-4594-af71-e2dab11a4a42_1.jpeg
    │   │           ├── ce7522a4-420f-40ab-9624-19f6333fa000_3.jpeg
    │   │           ├── cf09f529-2270-48a9-aa2d-1783ac83e656_2 (14).jpeg
    │   │           ├── cf2108f0-a7f1-42d8-be6c-07e52ad8f4ef_1.jpg
    │   │           ├── d121743f-a5ac-40c9-b2e0-fea8f9688281_1.jpeg
    │   │           ├── d16558ad-0c52-42f2-adff-b1c77ae1ad8f_1 (45).jpeg
    │   │           ├── d2dc38d9-1470-45ec-b4fd-aadfd4e55d74_13.jpg.jpeg
    │   │           ├── d61d7963-959c-4e57-9be5-a7341e6acc8e_1 (5).jpeg
    │   │           ├── d6ed767a-6990-4f0e-a79a-73e7791afdf0_1 (1).jpeg
    │   │           ├── d957167a-b284-42d8-aff5-610662091824_1.jpg
    │   │           ├── dabdb573-1f1d-40aa-a2dc-c601d676e6be_1 (1).jpeg
    │   │           ├── daf48381-2ff2-40ed-83a2-edb85c559a59_1.jpeg
    │   │           ├── db59244e-1de1-459c-b634-b49312a2e7c6_1.jpeg
    │   │           ├── dbc0fc65-58a0-494b-af72-69a9e8313ca3_6 (1).jpeg
    │   │           ├── dcab2a87-2833-4aa5-98cc-4dffd5e36ca8_8.jpg.jpeg
    │   │           ├── dcbaab11-d6cb-4f37-9ed5-ac4a8e9a22c0_1.jpeg
    │   │           ├── ddb8bb23-72dc-4456-9be6-f5f5530f694b_5 (2).jpeg
    │   │           ├── dfe0bb6d-8830-4945-811f-74a929be6c0f_1.jpeg
    │   │           ├── e0849cbf-812b-4c51-b9b5-b75c0873d9d2_1 (39).jpeg
    │   │           ├── e0c8decb-51ff-48c6-9c38-fcb792a4e20d_2 (4).jpeg
    │   │           ├── e15f0d4a-0bc3-4902-b54c-45c825ceb6f8_4 (7).jpeg
    │   │           ├── e17d9334-e9ad-4981-9564-21a8cfaa6de3_5 (4).jpeg
    │   │           ├── e1c41288-033a-49d6-958f-79c6be697cdd_1.jpeg
    │   │           ├── e20e1a13-34e2-4ab2-a038-45eae9f9701e_1.jpeg
    │   │           ├── e27f07f8-9ea1-4d8e-8a75-6c60eb086aee_2.jpeg
    │   │           ├── e2ec7bec-f59d-453d-903b-1ca2baebdb97_3.jpeg
    │   │           ├── e3149e14-5bad-46b0-bfd0-08f77bc2ac8b_2.jpg.jpeg
    │   │           ├── e321541d-4905-4550-94e3-fae9df130636_1 (8).jpeg
    │   │           ├── e360468a-1c75-4cae-bbe5-61153b2d6f4d_1 (38).jpeg
    │   │           ├── e3b9d17a-e330-4136-8dcf-5bf354635536_1 (43).jpeg
    │   │           ├── e3cde52e-b268-489f-b259-860747e9a026_3.jpg.jpeg
    │   │           ├── e462693e-4ae3-4f44-bfc3-9d597ce413e6_1.jpg
    │   │           ├── e5380614-abc8-4f55-9286-befb4f30396b_2 (11).jpeg
    │   │           ├── e6e03b68-7b83-4f41-9570-e7220a04abb8_1 (27).jpeg
    │   │           ├── e733f0dc-b564-488d-9648-62bb32ad51b6_5 (6).jpeg
    │   │           ├── e8570d79-470d-40b9-b88a-9d125a7e72c9_agilemethedology.jpg
    │   │           ├── e880dcd9-f9b0-49f4-811e-6ade20f31d49_4 (8).jpeg
    │   │           ├── e8bc18b4-c7a0-440c-b8e8-3dcae1063780_4 (2).jpeg
    │   │           ├── ea2dfba4-d5ea-4f72-9860-62ba8948c27f_1 (33).jpeg
    │   │           ├── eaa587c4-cf57-4c75-a207-483f31041d83_4.jpg.jpeg
    │   │           ├── ecb69209-476c-4ec6-90f9-1e67f3ec764e_1 (19).jpeg
    │   │           ├── ecc250dc-7e03-4bfc-89a2-6d2674433003_1 (16).jpeg
    │   │           ├── ecf78c36-1bf7-48fa-8b7b-5c06618526c5_2 (8).jpeg
    │   │           ├── ef253d71-1fc3-480b-880b-56edb2270e04_1 (25).jpeg
    │   │           ├── ef25c950-f964-4a6b-914c-7ef5be69f22b_1 (23).jpeg
    │   │           ├── f035a949-891e-48c5-ba72-f0f233004d91_2 (1).jpeg
    │   │           ├── f15331e6-0ba4-4f04-8c31-f1c7c5e817e1_2 (10).jpeg
    │   │           ├── f1b0beca-fd87-412e-85b8-668057c3c3c8_2 (1).jpeg
    │   │           ├── f2b18c0d-432c-43f9-ad0e-fcd80d9cec01_1 (37).jpeg
    │   │           ├── f3809f8d-78aa-4309-90b9-8ddd6ff6d4dd_2.jpeg
    │   │           ├── f3c02f57-8402-42ad-840b-feba74fcbd40_2.jpeg
    │   │           ├── f4ccc13b-3118-4da6-bf83-8bf308b81de2_2 (3).jpeg
    │   │           ├── f4ee22a4-29fc-4bbf-bfa7-de7ddb5f1e3c_4 (10).jpeg
    │   │           ├── f504fc76-6b34-4061-bd84-b26e8a1adf8c_6.jpg.jpeg
    │   │           ├── f59f2d99-1a2d-44d0-b3cb-dd0e97aad7b8_1 (23).jpeg
    │   │           ├── f6e481ca-db6a-4847-97d4-ae25fcac94db_2 (13).jpeg
    │   │           ├── f7355157-1849-4b5b-9221-995b6ee9165c_3 (12).jpeg
    │   │           ├── f78ea0cc-b8e3-4636-a756-2c5880901d61_1.jpg.jpeg
    │   │           ├── f7bbc930-53df-4e4f-9e01-8df1005462d7_2 (7).jpeg
    │   │           ├── f855a26d-1019-4770-b200-f82a5d12beb1_1.jpeg
    │   │           ├── f93e04a3-a603-46f7-bd5a-eecd2cfcf14d_4.jpg.jpeg
    │   │           ├── f999d8ab-229d-4a30-8edc-b496a9264491_1.jpg
    │   │           ├── f9ddacb2-ea45-4873-a472-89da48c2230d_2 (2).jpeg
    │   │           ├── fb7d2039-5878-4643-b390-79a583c1a006_1.jpg.jpeg
    │   │           ├── fbfd0665-e412-4737-b16d-0d6f34cc9596_Screenshot 2025-07-15 143635.png
    │   │           ├── fc5f9fa6-2344-46f6-bf00-38412c68e248_1.jpg
    │   │           ├── fc9ac892-8d66-4e62-bddc-65ce14dbb841_493837885_122152752836558855_6467953089869829267_n.jpg
    │   │           ├── fc9b32d1-5585-4387-b805-3554a2cd5a85_4.jpg.jpeg
    │   │           ├── fccd1e41-7a5c-4cc9-a5d7-8dcf2b59dc76_2.jpg.jpeg
    │   │           ├── fcea21a7-3921-4f5f-94de-7d580d811095_4 (3).jpeg
    │   │           ├── fd98179c-7382-4e20-8849-cd0b1fe04292_2 (15).jpeg
    │   │           ├── fdd07d0d-ef2c-46fb-8534-516fc769f872_1 (24).jpeg
    │   │           ├── fe5cd472-6a8a-4b07-a4f4-ba42e4842dfb_1 (45).jpeg
    │   │           └── fffc6e50-90e8-4551-b023-ba737bf4e6b3_4 (1).jpeg
    │   │       ├── seller
    │   │           └── business-logos
    │   │           │   ├── ad915628-e423-41b1-9539-ee02bd02693b_ball.jpg
    │   │           │   └── c866c781-f124-4da8-897a-59dd46bb1ebd_Adiddas.png
    │   │       └── sellers
    │   │           ├── 000ac597-08d0-432c-ab33-336c00a01003_picme.jpg
    │   │           ├── 1bb10ba6-526b-4422-8d7a-010b669421ec_Screenshot 2025-07-23 171241.png
    │   │           ├── 226efb0a-6264-42bf-bda0-ed3e026ec042_bussinedd.jpg
    │   │           ├── 5f9efb35-416f-462d-801a-cbeeb430216d_business.jpg
    │   │           ├── 7a68a3ac-77a6-4d51-a207-61a0ceef5590_bussinedd.jpg
    │   │           ├── 85e5eebb-6c46-4db9-9bcc-af95c56399d5_bussinedd.jpg
    │   │           ├── 8a05ccce-042c-4c10-8539-717ba98278a6_img4.jpg
    │   │           ├── 9f61af32-967f-4f52-93a6-36e0b8b4b22c_bussinedd.jpg
    │   │           ├── 9fd300df-a4a3-44bf-8615-a706708b11e5_bussinedd.jpg
    │   │           ├── a6053136-2174-499f-a22f-300ff0f56aa0_img3.jpg
    │   │           ├── bb540f69-e48a-46a9-8995-20ba4d5e6293_NudeKit.jpg
    │   │           ├── cd8b693f-9214-4527-9473-becf7cf546d9_casting operator ex.png
    │   │           ├── e4f4b2b3-af3e-4ad9-9f9c-7fbb6bfcee18_myphoto__1_-removebg-preview.png
    │   │           ├── ebd46bb2-6ecb-49e0-83cf-71c317e44afc_Login.jpg
    │   │           ├── f5712e18-58bd-4e96-8e97-879101bc2b45_Screenshot 2025-07-26 183720.png
    │   │           ├── ff16c539-8d32-4d6b-83c3-67fab8ac28a1_myphoto (1).jpg
    │   │           └── logos
    │   │               ├── 1b1b2aaf-805c-4793-97ef-5dd0909d6762_Adiddas.png
    │   │               ├── 1fa1f782-d8d1-4431-8e3b-5c34044357bf_Screenshot 2025-07-26 203711.png
    │   │               ├── 72876b41-741f-4660-acca-9c86f67b678c_Screenshot 2025-07-26 183720.png
    │   │               ├── 78fc54ee-b658-4fe3-a98a-a4a84fb1b55d_VichyLogo.png
    │   │               ├── 8df3cf8e-42b1-4116-a9b3-9088047b5b05_Adidas.png
    │   │               └── adb03395-de8e-4bca-a840-85ea92d17064_Adiddas.png
    ├── Jumia-Api.Application
    │   ├── Common
    │   │   └── Results
    │   │   │   ├── AuthResult.cs
    │   │   │   ├── OrderCreationResult.cs
    │   │   │   └── Result.cs
    │   ├── Dtos
    │   │   ├── AddressDtos
    │   │   │   ├── AddressDto.cs
    │   │   │   ├── CreateAddressDto.cs
    │   │   │   └── UpdateAddressDto.cs
    │   │   ├── AiDtos
    │   │   │   ├── AiQueryRequestDto.cs
    │   │   │   ├── AiQueryResponseDto.cs
    │   │   │   ├── AiQuestionRequestDto.cs
    │   │   │   └── AiQuestionResponseDto.cs
    │   │   ├── AuthDtos
    │   │   │   ├── EmailCheckDto.cs
    │   │   │   ├── ForgetPasswordDto.cs
    │   │   │   ├── LoginDto.cs
    │   │   │   ├── OtpVerifyDto.cs
    │   │   │   ├── PasswordSetupDto.cs
    │   │   │   ├── PersonalDetailsDto.cs
    │   │   │   ├── RegisterDto.cs
    │   │   │   └── ResetPasswordDto.cs
    │   │   ├── CartDto
    │   │   │   ├── AddToCartDto.cs
    │   │   │   ├── CartDto.cs
    │   │   │   ├── CartItemDto.cs
    │   │   │   └── UpdateCartItemDto.cs
    │   │   ├── CategoryDtos
    │   │   │   ├── CategoryResponseDto.cs
    │   │   │   ├── CreateCategoryDto.cs
    │   │   │   ├── MoveCategoryDto.cs
    │   │   │   └── UpdateCategoryDto.cs
    │   │   ├── ChatDTos
    │   │   │   ├── ChatDto.cs
    │   │   │   ├── ChatMessageDto.cs
    │   │   │   ├── CreateChatDto.cs
    │   │   │   └── SendMessageDto.cs
    │   │   ├── CouponDtos
    │   │   │   ├── ApplyCouponDto.cs
    │   │   │   ├── CouponDto.cs
    │   │   │   ├── CreateCouponDto.cs
    │   │   │   ├── UserCouponActionDto.cs
    │   │   │   ├── UserCouponDto.cs
    │   │   │   └── ValidateCouponResultDto.cs
    │   │   ├── CustomerDtos
    │   │   │   └── CustomerDTO.cs
    │   │   ├── OrderDtos
    │   │   │   ├── CancelOrderDTO.cs
    │   │   │   ├── CreateOrderDTO.cs
    │   │   │   ├── OrderDTO.cs
    │   │   │   ├── OrderItemDTO.cs
    │   │   │   ├── SubOrderDTO.cs
    │   │   │   └── UpdateOrderDTO.cs
    │   │   ├── PaymentDtos
    │   │   │   ├── PaymentRequetsDto.cs
    │   │   │   └── PaymentResponseDto.cs
    │   │   ├── ProductDtos
    │   │   │   ├── AttributeOptionDto.cs
    │   │   │   ├── AttributeOptionsRequestDto.cs
    │   │   │   ├── AttributeOptionsResponseDto.cs
    │   │   │   ├── FindVariantRequestDto.cs
    │   │   │   ├── Get
    │   │   │   │   ├── ProductDetailsDto.cs
    │   │   │   │   └── ProductsUIDto.cs
    │   │   │   ├── Post
    │   │   │   │   ├── AddProductDto.cs
    │   │   │   │   └── AddProductVariantDto.cs
    │   │   │   ├── ProductAttributeDto.cs
    │   │   │   ├── ProductFilterRequestDto.cs
    │   │   │   ├── ProductVariantDto.cs
    │   │   │   ├── UpdateProductDto.cs
    │   │   │   └── VariantAttributeDto.cs
    │   │   ├── RatingDtos
    │   │   │   ├── RatingCreateDto.cs
    │   │   │   ├── RatingInfoDto.cs
    │   │   │   └── RatingUpdateDto.cs
    │   │   ├── SellerDtos
    │   │   │   ├── CreateSellerDto.cs
    │   │   │   └── SellerInfo.cs
    │   │   ├── UserDtos
    │   │   │   ├── UpdateUserDto.cs
    │   │   │   └── UserProfileDto.cs
    │   │   └── WishlistDtos
    │   │   │   ├── AddToWishlistDto.cs
    │   │   │   ├── WishlistDto.cs
    │   │   │   └── WishlistItemDto.cs
    │   ├── Interfaces
    │   │   ├── IAddressService.cs
    │   │   ├── IAuthService.cs
    │   │   ├── ICampaignEmailService.cs
    │   │   ├── ICartService.cs
    │   │   ├── ICategoryService.cs
    │   │   ├── IChatService.cs
    │   │   ├── IConfirmationEmailService.cs
    │   │   ├── ICouponService.cs
    │   │   ├── IEmailService.cs
    │   │   ├── IFileService.cs
    │   │   ├── IJwtService.cs
    │   │   ├── IOrderService.cs
    │   │   ├── IOtpService.cs
    │   │   ├── IPaymentService.cs
    │   │   ├── IProductAiService.cs
    │   │   ├── IProductService.cs
    │   │   ├── IRatingService.cs
    │   │   ├── IRecommendationService.cs
    │   │   ├── ISellerService.cs
    │   │   ├── IUserCouponService.cs
    │   │   ├── IUserService.cs
    │   │   └── IWishlistService.cs
    │   ├── Jumia-Api.Application.csproj
    │   ├── MappingProfiles
    │   │   ├── CartMapping.cs
    │   │   ├── CouponMapping.cs
    │   │   ├── OrderMapping.cs
    │   │   ├── ProductsMapping.cs
    │   │   ├── UserMapping.cs
    │   │   └── WishlistMapping.cs
    │   ├── Services
    │   │   ├── AddressService.cs
    │   │   ├── AuthSerrvice.cs
    │   │   ├── CartService.cs
    │   │   ├── CategoryService .cs
    │   │   ├── ConfirmationEmailService .cs
    │   │   ├── CouponService.cs
    │   │   ├── EmailService.cs
    │   │   ├── FileService.cs
    │   │   ├── JwtService.cs
    │   │   ├── OrderService.cs
    │   │   ├── OtpService.cs
    │   │   ├── ProductService.cs
    │   │   ├── RatingService.cs
    │   │   ├── SellerService.cs
    │   │   ├── UserCouponService.cs
    │   │   ├── UserService.cs
    │   │   └── WishlistService.cs
    │   ├── bin
    │   │   └── Debug
    │   │   │   └── net9.0
    │   │   │       ├── Jumia-Api.Application.deps.json
    │   │   │       ├── Jumia-Api.Application.dll
    │   │   │       ├── Jumia-Api.Application.pdb
    │   │   │       ├── Jumia-Api.Application.runtimeconfig.json
    │   │   │       ├── Jumia-Api.Domain.dll
    │   │   │       ├── Jumia-Api.Domain.pdb
    │   │   │       └── LatoFont
    │   │   │           ├── Lato-Black.ttf
    │   │   │           ├── Lato-BlackItalic.ttf
    │   │   │           ├── Lato-Bold.ttf
    │   │   │           ├── Lato-BoldItalic.ttf
    │   │   │           ├── Lato-ExtraBold.ttf
    │   │   │           ├── Lato-ExtraBoldItalic.ttf
    │   │   │           ├── Lato-ExtraLight.ttf
    │   │   │           ├── Lato-ExtraLightItalic.ttf
    │   │   │           ├── Lato-Italic.ttf
    │   │   │           ├── Lato-Light.ttf
    │   │   │           ├── Lato-LightItalic.ttf
    │   │   │           ├── Lato-Medium.ttf
    │   │   │           ├── Lato-MediumItalic.ttf
    │   │   │           ├── Lato-Regular.ttf
    │   │   │           ├── Lato-SemiBold.ttf
    │   │   │           ├── Lato-SemiBoldItalic.ttf
    │   │   │           ├── Lato-Thin.ttf
    │   │   │           ├── Lato-ThinItalic.ttf
    │   │   │           └── OFL.txt
    │   └── obj
    │   │   ├── Debug
    │   │       └── net9.0
    │   │       │   ├── .NETCoreApp,Version=v9.0.AssemblyAttributes.cs
    │   │       │   ├── Jumia-Ap.E81A5420.Up2Date
    │   │       │   ├── Jumia-Api.Application.AssemblyInfo.cs
    │   │       │   ├── Jumia-Api.Application.AssemblyInfoInputs.cache
    │   │       │   ├── Jumia-Api.Application.GeneratedMSBuildEditorConfig.editorconfig
    │   │       │   ├── Jumia-Api.Application.GlobalUsings.g.cs
    │   │       │   ├── Jumia-Api.Application.assets.cache
    │   │       │   ├── Jumia-Api.Application.csproj.AssemblyReference.cache
    │   │       │   ├── Jumia-Api.Application.csproj.BuildWithSkipAnalyzers
    │   │       │   ├── Jumia-Api.Application.csproj.CoreCompileInputs.cache
    │   │       │   ├── Jumia-Api.Application.csproj.FileListAbsolute.txt
    │   │       │   ├── Jumia-Api.Application.dll
    │   │       │   ├── Jumia-Api.Application.genruntimeconfig.cache
    │   │       │   ├── Jumia-Api.Application.pdb
    │   │       │   ├── Jumia-Api.Application.sourcelink.json
    │   │       │   ├── ref
    │   │       │       └── Jumia-Api.Application.dll
    │   │       │   └── refint
    │   │       │       └── Jumia-Api.Application.dll
    │   │   ├── Jumia-Api.Application.csproj.nuget.dgspec.json
    │   │   ├── Jumia-Api.Application.csproj.nuget.g.props
    │   │   ├── Jumia-Api.Application.csproj.nuget.g.targets
    │   │   ├── project.assets.json
    │   │   └── project.nuget.cache
    ├── Jumia-Api.Domain
    │   ├── Enums
    │   │   ├── ApprovalStatus.cs
    │   │   ├── Gender.cs
    │   │   ├── JobStatus.cs
    │   │   ├── JobType.cs
    │   │   └── Status.cs
    │   ├── Interfaces
    │   │   ├── Repositories
    │   │   │   ├── IAddressRepo.cs
    │   │   │   ├── ICampaignJobRequestRepo.cs
    │   │   │   ├── ICartItemRepo.cs
    │   │   │   ├── ICartRepo.cs
    │   │   │   ├── ICategoryRepo .cs
    │   │   │   ├── IChatRepository.cs
    │   │   │   ├── ICouponRepo.cs
    │   │   │   ├── ICustomerRepo.cs
    │   │   │   ├── IGenericRepo.cs
    │   │   │   ├── IOrderItemRepo.cs
    │   │   │   ├── IOrderRepository.cs
    │   │   │   ├── IProductAttributeRepo.cs
    │   │   │   ├── IProductAttributeValue.cs
    │   │   │   ├── IProductRepo.cs
    │   │   │   ├── IRatingRepo.cs
    │   │   │   ├── ISellerRepo.cs
    │   │   │   ├── IUserCouponRepo.cs
    │   │   │   ├── IUserRepository.cs
    │   │   │   ├── IVariantAttributeRepo.cs
    │   │   │   ├── IVariantRepo.cs
    │   │   │   ├── IWishlistItemRepo.cs
    │   │   │   ├── IWishlistRepo.cs
    │   │   │   └── IsuborderRepo.cs
    │   │   └── UnitOfWork
    │   │   │   └── IUnitOfWork.cs
    │   ├── Jumia-Api.Domain.csproj
    │   ├── Models
    │   │   ├── Address.cs
    │   │   ├── Admin.cs
    │   │   ├── Affiliate.cs
    │   │   ├── AffiliateCommission.cs
    │   │   ├── AffiliateSellerRelationship.cs
    │   │   ├── AffiliateWithdrawal.cs
    │   │   ├── AppUser.cs
    │   │   ├── CampaignJobRequest.cs
    │   │   ├── Cart.cs
    │   │   ├── CartItem.cs
    │   │   ├── Category.cs
    │   │   ├── Chat.cs
    │   │   ├── ChatMessage.cs
    │   │   ├── Coupon.cs
    │   │   ├── Customer.cs
    │   │   ├── HelpfulRating.cs
    │   │   ├── JwtSettings.cs
    │   │   ├── Order.cs
    │   │   ├── OrderItem.cs
    │   │   ├── Payment.cs
    │   │   ├── Product.cs
    │   │   ├── ProductAttribute.cs
    │   │   ├── ProductAttributeValue.cs
    │   │   ├── ProductImage.cs
    │   │   ├── ProductVariant.cs
    │   │   ├── Rating.cs
    │   │   ├── ReviewImage.cs
    │   │   ├── Seller.cs
    │   │   ├── SubOrder.cs
    │   │   ├── UserCoupon.cs
    │   │   ├── VariantAttribute.cs
    │   │   ├── WishList.cs
    │   │   └── WishListItem.cs
    │   ├── PagedResult.cs
    │   ├── TopSellingProducts.cs
    │   ├── bin
    │   │   └── Debug
    │   │   │   └── net9.0
    │   │   │       ├── Jumia-Api.Domain.deps.json
    │   │   │       ├── Jumia-Api.Domain.dll
    │   │   │       ├── Jumia-Api.Domain.pdb
    │   │   │       ├── Jumia-Api.Domain.runtimeconfig.json
    │   │   │       └── LatoFont
    │   │   │           ├── Lato-Black.ttf
    │   │   │           ├── Lato-BlackItalic.ttf
    │   │   │           ├── Lato-Bold.ttf
    │   │   │           ├── Lato-BoldItalic.ttf
    │   │   │           ├── Lato-ExtraBold.ttf
    │   │   │           ├── Lato-ExtraBoldItalic.ttf
    │   │   │           ├── Lato-ExtraLight.ttf
    │   │   │           ├── Lato-ExtraLightItalic.ttf
    │   │   │           ├── Lato-Italic.ttf
    │   │   │           ├── Lato-Light.ttf
    │   │   │           ├── Lato-LightItalic.ttf
    │   │   │           ├── Lato-Medium.ttf
    │   │   │           ├── Lato-MediumItalic.ttf
    │   │   │           ├── Lato-Regular.ttf
    │   │   │           ├── Lato-SemiBold.ttf
    │   │   │           ├── Lato-SemiBoldItalic.ttf
    │   │   │           ├── Lato-Thin.ttf
    │   │   │           ├── Lato-ThinItalic.ttf
    │   │   │           └── OFL.txt
    │   └── obj
    │   │   ├── Debug
    │   │       └── net9.0
    │   │       │   ├── .NETCoreApp,Version=v9.0.AssemblyAttributes.cs
    │   │       │   ├── Jumia-Api.Domain.AssemblyInfo.cs
    │   │       │   ├── Jumia-Api.Domain.AssemblyInfoInputs.cache
    │   │       │   ├── Jumia-Api.Domain.GeneratedMSBuildEditorConfig.editorconfig
    │   │       │   ├── Jumia-Api.Domain.GlobalUsings.g.cs
    │   │       │   ├── Jumia-Api.Domain.assets.cache
    │   │       │   ├── Jumia-Api.Domain.csproj.AssemblyReference.cache
    │   │       │   ├── Jumia-Api.Domain.csproj.BuildWithSkipAnalyzers
    │   │       │   ├── Jumia-Api.Domain.csproj.CoreCompileInputs.cache
    │   │       │   ├── Jumia-Api.Domain.csproj.FileListAbsolute.txt
    │   │       │   ├── Jumia-Api.Domain.dll
    │   │       │   ├── Jumia-Api.Domain.genruntimeconfig.cache
    │   │       │   ├── Jumia-Api.Domain.pdb
    │   │       │   ├── Jumia-Api.Domain.sourcelink.json
    │   │       │   ├── ref
    │   │       │       └── Jumia-Api.Domain.dll
    │   │       │   └── refint
    │   │       │       └── Jumia-Api.Domain.dll
    │   │   ├── Jumia-Api.Domain.csproj.nuget.dgspec.json
    │   │   ├── Jumia-Api.Domain.csproj.nuget.g.props
    │   │   ├── Jumia-Api.Domain.csproj.nuget.g.targets
    │   │   ├── project.assets.json
    │   │   └── project.nuget.cache
    └── Jumia-Api.Infrastructure
    │   ├── Context
    │       └── Migrations
    │       │   └── JumiaDbContextModelSnapshot.cs
    │   ├── External Services
    │       ├── CampaignEmailService .cs
    │       ├── CampaignEmailWorker.cs
    │       ├── ChatService.cs
    │       ├── PaymentService.cs
    │       ├── ProductAiService.cs
    │       ├── RecommendationService.cs
    │       ├── RedisKeyExpiryService.cs
    │       ├── ReportKeyHandler.cs
    │       └── SendGridEmailService.cs
    │   ├── Hubs
    │       └── ChatHub.cs
    │   ├── Jumia-Api.Infrastructure.csproj
    │   ├── Migrations
    │       ├── 20250802090636_lonh.Designer.cs
    │       └── 20250802090636_lonh.cs
    │   ├── Presistence
    │       ├── Context
    │       │   ├── Configuration
    │       │   │   ├── OrderConfig.cs
    │       │   │   └── SubOrderConfig.cs
    │       │   └── JumiaDbContext.cs
    │       ├── Repositories
    │       │   ├── AddressRepo.cs
    │       │   ├── CampaignJobRequestRepo.cs
    │       │   ├── CartItemRepo.cs
    │       │   ├── CartRepo.cs
    │       │   ├── CategoryRepository .cs
    │       │   ├── ChatRepository.cs
    │       │   ├── CouponRepository.cs
    │       │   ├── CustomerRepo.cs
    │       │   ├── GenericRepo.cs
    │       │   ├── OrderItemRepo.cs
    │       │   ├── OrderRepository.cs
    │       │   ├── ProductAttributeRepo.cs
    │       │   ├── ProductAttributeValueRepo.cs
    │       │   ├── ProductRepo.cs
    │       │   ├── RatingRepo.cs
    │       │   ├── SellerRepo.cs
    │       │   ├── SuborderRepo.cs
    │       │   ├── UserCouponRepository.cs
    │       │   ├── VariantAttributeRepo.cs
    │       │   ├── VariantRepo.cs
    │       │   ├── WishlistItemRepo.cs
    │       │   └── WishlistRepo.cs
    │       └── UnitOfWork
    │       │   └── UnitOfWork.cs
    │   ├── bin
    │       └── Debug
    │       │   └── net9.0
    │       │       ├── Jumia-Api.Application.dll
    │       │       ├── Jumia-Api.Application.pdb
    │       │       ├── Jumia-Api.Domain.dll
    │       │       ├── Jumia-Api.Domain.pdb
    │       │       ├── Jumia-Api.Infrastructure.deps.json
    │       │       ├── Jumia-Api.Infrastructure.dll
    │       │       ├── Jumia-Api.Infrastructure.pdb
    │       │       ├── Jumia-Api.Infrastructure.runtimeconfig.json
    │       │       └── LatoFont
    │       │           ├── Lato-Black.ttf
    │       │           ├── Lato-BlackItalic.ttf
    │       │           ├── Lato-Bold.ttf
    │       │           ├── Lato-BoldItalic.ttf
    │       │           ├── Lato-ExtraBold.ttf
    │       │           ├── Lato-ExtraBoldItalic.ttf
    │       │           ├── Lato-ExtraLight.ttf
    │       │           ├── Lato-ExtraLightItalic.ttf
    │       │           ├── Lato-Italic.ttf
    │       │           ├── Lato-Light.ttf
    │       │           ├── Lato-LightItalic.ttf
    │       │           ├── Lato-Medium.ttf
    │       │           ├── Lato-MediumItalic.ttf
    │       │           ├── Lato-Regular.ttf
    │       │           ├── Lato-SemiBold.ttf
    │       │           ├── Lato-SemiBoldItalic.ttf
    │       │           ├── Lato-Thin.ttf
    │       │           ├── Lato-ThinItalic.ttf
    │       │           └── OFL.txt
    │   └── obj
    │       ├── Debug
    │           └── net9.0
    │           │   ├── .NETCoreApp,Version=v9.0.AssemblyAttributes.cs
    │           │   ├── Jumia-Ap.F26406A7.Up2Date
    │           │   ├── Jumia-Api.Infrastructure.AssemblyInfo.cs
    │           │   ├── Jumia-Api.Infrastructure.AssemblyInfoInputs.cache
    │           │   ├── Jumia-Api.Infrastructure.GeneratedMSBuildEditorConfig.editorconfig
    │           │   ├── Jumia-Api.Infrastructure.GlobalUsings.g.cs
    │           │   ├── Jumia-Api.Infrastructure.assets.cache
    │           │   ├── Jumia-Api.Infrastructure.csproj.AssemblyReference.cache
    │           │   ├── Jumia-Api.Infrastructure.csproj.BuildWithSkipAnalyzers
    │           │   ├── Jumia-Api.Infrastructure.csproj.CoreCompileInputs.cache
    │           │   ├── Jumia-Api.Infrastructure.csproj.FileListAbsolute.txt
    │           │   ├── Jumia-Api.Infrastructure.dll
    │           │   ├── Jumia-Api.Infrastructure.genruntimeconfig.cache
    │           │   ├── Jumia-Api.Infrastructure.pdb
    │           │   ├── Jumia-Api.Infrastructure.sourcelink.json
    │           │   ├── ref
    │           │       └── Jumia-Api.Infrastructure.dll
    │           │   └── refint
    │           │       └── Jumia-Api.Infrastructure.dll
    │       ├── Jumia-Api.Infrastructure.csproj.nuget.dgspec.json
    │       ├── Jumia-Api.Infrastructure.csproj.nuget.g.props
    │       ├── Jumia-Api.Infrastructure.csproj.nuget.g.targets
    │       ├── project.assets.json
    │       └── project.nuget.cache
