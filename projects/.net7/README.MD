# .NET 7 (21)

Samples in this section require .NET 7 Preview 7. You can download it from [here](https://dotnet.microsoft.com/en-us/download/dotnet/7.0).

* [Infer dependency from action parameter](mvc-infer-dependency-from-action)

  There is no need for `[FromServices]` attribute anymore to inject a dependency to your action method.

* [Typed Results - 1](typed-results-1)
  
  `Microsoft.AspNetCore.Http.TypedResults` static class is the “typed” equivalent of the existing `Microsoft.AspNetCore.Http.Results` class.

* [WithOpenApi - 1](open-api-1)

  This sample demonstrate the usage of `WithOpenApi` extension method available in  `Microsoft.AspNetCore.OpenApi` to customize OpenAPI operation information.

* [Results<> Union Type](open-api-2)

  `Results<TResult1, TResult2, TResultN>` provides better description of the result of the operation that OpenAPI/Swagger can use in describing the API.

## Endpoint Filter

* [Endpoint Filter - 1](endpoint-filter-1)

  This sample shows how to apply an Endpoint filter to your minimal API.

* [Endpoint Filter - 2](endpoint-filter-2)

  This sample shows how to apply multiple Endpoint filters to your minimal APIs.

* [Endpoint Filter - 3](endpoint-filter-3)

  This examples shows the sequence of code execution before `RouteHandlerFilterDelegate ` and after `RouteHandlerFilterDelegate` in multiple endpoint filters.

* [Endpoint Filter - 4](endpoint-filter-4)

  Use `IStatusCodeHttpResult` to detect return result in filter.

## Route Group

* [Route Group - 1](map-group-1)

  `MapGroup()` extension methods allow grouping of endpoints with a common prefix. It also allow group metadata to be attached to the group.

* [Route Group - 2](map-group-2)

  Use `.WithTags()`, `.WithDescription()`, `.WithSummary()` to enrich OpenAPI information for all the endpoints in the group.

* [Route Group - 3](map-group-3)

  Use `.ExcludeFromDescription` to exclude endpoints from OpenAPI description.

## Authentication

* [Authentication - JWT](authentication-1)

  This sample shows the usage of the simplified authentication and authorization via `builder.AddAuthentication().AddJwtBearer();`.

* [Authentication - Cookie](authentication-2)

  This sample shows the usage of the simplified authentication and authorization via `builder.AddAuthentication().AddCookie();`.

* [Authentication - Mixed](authentication-3)

  This sample shows how to use both JWT and Cookie authentications in the same application.

## Output cache

* [Output Cache - 1](output-cache-1)

  This sample shows how to use the `OutputCache` middleware using basic options.

* [Output Cache - 2](output-cache-2)

  This sample shows how to use the `OutputCache` middleware and vary them by one or more query string.

## gRPC

* [gRPC - 13](grpc-13)

  This sample shows how to make a GET HTTP call to a gRPC endpoint via gRPC JSON transcoding.

* [gRPC - 14](grpc-14)

  This sample shows how to make a POST HTTP call to a gRPC endpoint via gRPC JSON transcoding.

* [gRPC - 15](grpc-15)

  This sample shows how to make a POST HTTP call to a gRPC endpoint via gRPC JSON transcoding by combining route parameter and body.

* [gRPC - 16](grpc-16)

  This sample shows how to make a PUT HTTP call to a gRPC endpoint via gRPC JSON transcoding.

* [gRPC - 17](grpc-17)

  This sample shows how to make a PATCH HTTP call to a gRPC endpoint via gRPC JSON transcoding.
